
# ft_printf 42

ft_printf is a project at 42 School that requires you to implement your own version of the C standard printf function. The goal is to replicate its behavior while handling multiple format specifiers.

## Requirements
 * A Unix-based operating system (Linux/MacOS)
 * C programming language

## Setup
Clone the repository :
```
  git clone https://github.com/BouhcineAmezouar7/ft_printf.git
  cd ft_printf
```

Compile the project:
```
 make
```
This will generate the libftprintf.a static library

## Usage
Using ft_printf

Include ft_printf.h in your project and link the library:
```
#include "ft_printf.h"

int main()
{
    ft_printf("Hello, %s! The number is %d.\n", "world", 42);
    return 0;
}
```

Compile and run:
```
gcc -Wall -Wextra -Werror main.c libftprintf.a -o test_printf
./test_printf
```
Function Prototype
```
int ft_printf(const char *format, ...);
```
* Mimics the standard printf function.

* Supports multiple format specifiers.

* Returns the number of characters printed.

## Supported Format Specifiers

* %c : Prints a single character

* %s : Prints a string

* %p : Prints a pointer address

* %d : Prints a decimal integer

* %i : Prints an integer

* %u : Prints an unsigned integer

* %x : Prints a hexadecimal number (lowercase)

* %X : Prints a hexadecimal number (uppercase)

* %% : Prints a percent sign


## Features
* Handles variable arguments.

* Manages format specifiers correctly.

* Works similarly to the standard printf.

