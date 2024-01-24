# ft_printf

This is the implementation of the `printf` function in C, named `ft_printf`, as part of the 42 School curriculum.

## Table of Contents

- [Description](#description)
- [Functionality](#functionality)
- [Example](#example) 
- [Usage](#usage)

## Description

The `ft_printf` project is an implementation of the standard C library function `printf`. It supports various format specifiers and provides a way to format and print data.

## Functionality

The `ft_printf` function supports the following format specifiers:

- `%c`: Character
- `%s`: String
- `%p`: Pointer
- `%d` or `%i`: Integer
- `%u`: Unsigned Integer
- `%x`: Hexadecimal (lowercase)
- `%X`: Hexadecimal (uppercase)
- `%%`: Percent sign

## Example

Here is an example demonstrating the usage of `ft_printf`:

```c
#include "ft_printf.h"

int main(void)
{
    ft_printf("Hello, %s! This is a number: %d\n", "User", 42);
    return 0;
}
```

## Usage

To use the `ft_printf` function in your project, follow these steps:

1. Clone the repository:

    ```bash
    https://github.com/Madelsa/42-ft_printf.git
    ```

2. Include the header file in your `.c` file:

    ```c
    #include "ft_printf.h"
    ```

3. Compile the `ft_printf` project by running the following command:

    ```bash
    make
    ```
   
4. Compile your `.c` file that contains the `main` function:

    ```bash
    gcc my_program.c libftprintf.a
    ```

5. Run your `a.out` executable:
   
   ```bash
   ./a.out
   ```
6. Now you can use `ft_printf` in your code as you would use the standard `printf` function.
