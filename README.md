## printf

_printf is a custom implementation of the C programming function printf. This project is an application of the C programming knowledge.

### Project Requirements

1. All files will be compiled on Ubuntu 20.04 LTS, using the options

`gcc -Wall -Werror -Wextra -pedantic -std=gnu89 *.c`

2. Global variables are not allowed

3. Authorized functions and macros:

`write (man 2 write)`

`malloc (man 3 malloc)`

`free (man 3 free)`

`va_start (man 3 va_start)`

`va_end (man 3 va_end)`

`va_copy (man 3 va_copy)`

`va_arg (man 3 va_arg)`

### Mandatory Tasks

Task 0: Write function that handles the conversion specifiers c, s, and %. Use 0-main.c to test the function.

Task 1: Handle conversion specifiers d, i.

**Create a man page for your function.**
 
### Advanced Tasks

Task 2: Handle conversion specifier b. Use 2-main.c to test the function.

Task 3: Handle conversion specifiers u, o, x, X.

Task 4: Use a local buffer of 1024 chars in order to call write as little as possible.

Task 5: Handle conversion specifier S. Use 5-main.c to test the function.

Task 6: Handle conversion specifier p.

Task 7: Handle flag characters +, space, and # for non-custom conversion specifiers.

Task 8: Handle length modifiers l and h for non-custom conversion specifiers.

Task 9: Handle the field width for non-custom conversion specifiers.

Task 10: Handle the precision for non-custom conversion specifiers.

Task 11: Handle the 0 flag character for non-custom conversion specifiers.

Task 12: Handle the - flag character for non-custom conversion specifiers.

Task 13: Handle the custom conversion specifier r that prints the reversed string.

Task 14: Handle the custom conversion specifier R that prints the rot13'ed string.

Task 15: All above options should work well together.

### File Descriptions

_printf.c: - contains the fucntion _printf, which uses the prototype int _printf(const char *format, ...);. The format string is composed of zero or more directives. See man 3 printf for more detail. _printf will return the number of characters printed (excluding the null byte used to end output to strings) and will write output to stdout, the standard output stream.

_putchar.c: - contains the function _putchar, which writes a character to stdout.

main.h: - contains all function prototypes used for _printf.

man_3_printf: - manual page for the custom _printf function.

print_chars.c: - contains the functions print_c, print_s, print_S, and print_r which handle the conversion specifiers c, s, S, and r, respectively, as well as hex_print, which prints a char's ascii value in uppercase hex

print_numbers.c: - contains the functions print_i and print_d, which handle the conversion specifiers i and d, respectively

print_hex.c: - contains the functions print_hex, which prints an unsigned int in hexidecimal form, print_x, print_X, and print_p, which handle the conversion specifiers x, X, and p, respectively

print_unsigned_int.c: - contains the functions print_u, print_o, and print_b, which handle the conversion specifiers u, o, and b, respectively

print_rot13.c - contains the function print_R, which handles the conversion specifier R

### Authors

Leroy BUliro | @leroysb

Immanuel Mwiti | @Mna0o7
