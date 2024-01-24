# ft_printf

This is the implementation of the `printf` function in C, named `ft_printf`, as part of the 42 School curriculum.

## Table of Contents

- [Description](#description)
- [Usage](#usage)
- [Functionality](#functionality)
- [Example](#example) 
- [How to Compile](#how-to-compile)

## Description

The `ft_printf` project is an implementation of the standard C library function `printf`. It supports various format specifiers and provides a way to format and print data.

## Usage

To use the `ft_printf` function in your project, follow these steps:

1. Clone the repository:

    ```bash
    https://github.com/Madelsa/42-ft_printf.git
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
- `%%`: Percent sign

For detailed usage and additional options, refer to the [man page](#) (Replace `#` with the actual link once it's available).

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

## How to Compile

To compile the `ft_printf` project, run the following command:

```bash
make
```

After that, compile the `.c` file that contains the `main` function:

```bash
gcc my_program.c libftprintf.a
```

Finally, run your `a.out` executable:

```bash
./a.out
```
