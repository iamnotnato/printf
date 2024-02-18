## printf

### Purpose

`printf` is a command-line tool inspired by the classic `printf` function from the C programming language. It provides a flexible and powerful way to format and print data in a variety of ways.

### Features

- Supports a wide range of format specifiers, including:
    - `%s`: String
    - `%d`: Decimal integer
    - `%f`: Floating-point number
    - `%x`: Hexadecimal integer
    - `%b`: Binary integer
- Allows for custom formatting options, such as:
    - Precision (number of decimal places)
    - Field width (minimum number of characters)
    - Alignment (left, right, or center)
- Can read data from standard input or from a specified file
- Can write data to standard output or to a specified file

### Technologies Used

- C++
- Standard C++ Library

### Getting Started

To get started with `printf`, simply clone the repository and build the executable:

```
git clone https://github.com/iamnotnato/printf
cd printf
mkdir build
cd build
cmake ..
make
```

Once the executable is built, you can use it to format and print data in a variety of ways. For example, the following command will print the string "Hello, world!" to the console:

```
./printf "%s\n" "Hello, world!"
```

### Git Clone

```
git clone https://github.com/iamnotnato/printf.git
```

### Contribution Guidelines

Contributions are welcome! Please read the [contribution guidelines](CONTRIBUTING.md) before submitting a pull request.

### License

`printf` is licensed under the MIT License.

### Contact

For any questions or support, please contact the maintainer through [GitHub](https://github.com/iamnotnato).
