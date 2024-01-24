# ft_printf

This is the implementation of the `printf` function in C, named `ft_printf`, as part of the 42 School curriculum.

## Table of Contents

- [Description](#description)
- [Usage](#usage)
- [Functionality](#functionality)
- [How to Compile](#how-to-compile)
- [Examples](#examples)
- [Contributing](#contributing)
- [License](#license)

## Description

The `ft_printf` project is an implementation of the standard C library function `printf`. It supports various format specifiers and provides a way to format and print data.

## Usage

To use the `ft_printf` function in your project, follow these steps:

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/ft_printf.git
    ```

2. Include the header file in your source code:

    ```c
    #include "ft_printf.h"
    ```

3. Compile your code with the `ft_printf` source files:

    ```bash
    gcc -Wall -Wextra -Werror -I path/to/ft_printf main.c path/to/ft_printf/*.c -o your_executable
    ```

4. Use `ft_printf` in your code as you would use the standard `printf` function.

## Functionality

The `ft_printf` function supports the following format specifiers:

- `%c`: Character
- `%s`: String
- `%p`: Pointer
- `%d` or `%i`: Integer
- `%u`: Unsigned Integer
- `%x`: Hexadecimal (lowercase)
- `%X`: Hexadecimal (uppercase)
- `%o`: Octal
- `%f`: Floating-point
- `%%`: Percent sign

### Additional Format Specifiers

- `%e`: Scientific notation (lowercase)
- `%E`: Scientific notation (uppercase)
- `%g`: Shortest representation of `%e` or `%f`
- `%G`: Shortest representation of `%E` or `%f`
- `%a`: Hexadecimal floating-point (lowercase)
- `%A`: Hexadecimal floating-point (uppercase)

For detailed usage and additional options, refer to the [man page](#) (Replace `#` with the actual link once it's available).

## How to Compile

To compile the `ft_printf` project, run the following commands:

```bash
make
