# Principle of Inclusion and Exclusion using C Graphics

This project demonstrates the **Principle of Inclusion and Exclusion** using C graphics. The inclusion-exclusion principle is a fundamental combinatorial method used to calculate the size of the union of several sets by using the sizes of the individual sets and their intersections.


## Introduction

The Principle of Inclusion and Exclusion (PIE) is a useful tool in combinatorics to calculate the union of multiple sets. This project visualizes the concept using C language graphics, providing users with an intuitive understanding of how the principle works.

### Principle Overview:
If you want to find the union of three sets, the inclusion-exclusion principle states:

\[
|A \cup B \cup C| = |A| + |B| + |C| - |A \cap B| - |A \cap C| - |B \cap C| + |A \cap B \cap C|
\]

This program implements and visualizes this principle.

## Features

- Graphical representation of sets using C graphics library.
- Calculation of union, intersection, and complements.
- Visualization of the set inclusion and exclusion principle with dynamic display.
- User-friendly interface to demonstrate combinatorial results.

## Requirements

To run this project, you'll need:

- C compiler (GCC or Turbo C recommended)
- Graphics library support (such as `graphics.h` in Turbo C)

## Installation

1. Clone this repository:
    ```bash
    git clone https://github.com/ashikbp123/Principle-of-Inclusion-and-Exclusion-using-C-graphics.git
    ```
2. Navigate to the project directory:
    ```bash
    cd Principle-of-Inclusion-and-Exclusion-using-C-graphics
    ```

3. Make sure you have a C compiler with support for `graphics.h`. If you're using Turbo C, copy the necessary graphics files to your compiler's library directory.

## Usage

1. Compile the code using your C compiler:
    - For GCC (with required graphics library support):
      ```bash
      gcc -o inclusion_exclusion inclusion_exclusion.c -lgraph
      ```

    - For Turbo C, open the project in Turbo C and run it directly.

2. Run the compiled program:
    ```bash
    ./inclusion_exclusion
    ```

3. The program will visualize the principle of inclusion and exclusion using graphical circles representing different sets and their intersections.

## Contributing

Contributions are welcome! If you would like to contribute to this project, please open an issue or submit a pull request. Make sure to follow the contribution guidelines.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
