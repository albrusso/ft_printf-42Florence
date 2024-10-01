# ft_printf [42Cursus]

## Overview

**ft_printf** is a custom implementation of the `printf` function in C. This project is part of the 42 curriculum and aims to enhance understanding of formatted output in C programming.

## Features

- Supports various format specifiers, including integers, strings, characters, and more.
- Implements additional flags for formatting, such as precision and width.
- Handles different data types with proper type checking.
- Written in **C** and adheres to the 42 coding standards.

## Format Specifiers

The following format specifiers are supported:

- `%c` - Character
- `%s` - String
- `%d` - Signed integer
- `%i` - Signed integer
- `%u` - Unsigned integer
- `%x` - Unsigned hexadecimal (lowercase)
- `%X` - Unsigned hexadecimal (uppercase)
- `%p` - Pointer address

## How to Use

To use **ft_printf** in your project:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/ft_printf.git

2. Compile the library:
   ```bash
   make

3. Include the header in your code:
   ```bash
   #include "ft_printf.h"

4. Call the function in your code:
   ```bash
   ft_printf("Hello, %s!\n", "world");

## License

This project is for educational purposes as part of the 42Cursus and adheres to the rules of the 42 school. Feel free to review and adapt the code, but do not copy it directly for personal submissions.
