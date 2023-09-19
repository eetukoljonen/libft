# libft

libft is a custom C library that re-implements some of the standard C library functions and includes additional custom functions. This library is intended to be used in our future projects in Hive Helsinki coding school.

# Features
 * Re-implementation of standard C library functions such as **strlen**, **strcpy**, **memset**, etc.
 * Custom functions designed to simplify common programming tasks.
 * A Makefile for easy compilation into a **libft.a** library.

# Usage

1. Clone this repository on your local machine.
```
git clone https://github.com/eetukoljonen/libft.git
```
2. Compile the library.
```
make
```
This will generate a libft.a library file.

3. In your C source code file, include the desired header files from the libft library. For example:
```
#include "libft.h"
```
4. Compile your program linking it with the **libft.a** library
```
gcc -o myprogram myprogram.c libft.a
```

