libft<br>
<br>
libft is a 42 school project where you are required to create your own C library by implementing common functions that are typically provided by the C standard library. The goal of this project is to understand how these functions work and improve your programming skills in C.<br>
<br>
Functionality:<br>
<br>
In this project, you will implement functions for basic string manipulation, memory management, conversion, and other utilities. Some of the main functions that should be implemented include:<br>
<br>
- `ft_memset`<br>
- `ft_bzero`<br>
- `ft_memcpy`<br>
- `ft_memmove`<br>
- `ft_memchr`<br>
- `ft_memcmp`<br>
- `ft_strlen`<br>
- `ft_strdup`<br>
- `ft_strcpy`<br>
- `ft_strncpy`<br>
- `ft_strcat`<br>
- `ft_strncat`<br>
- `ft_strchr`<br>
- `ft_strrchr`<br>
- `ft_strcmp`<br>
- `ft_strncmp`<br>
- `ft_atoi`<br>
- `ft_isdigit`<br>
- `ft_isalpha`<br>
- `ft_isalnum`<br>
- `ft_toupper`<br>
- `ft_tolower`<br>
<br>
Requirements:<br>
<br>
- Implement each function with its correct prototype.<br>
- Do not use the corresponding standard library functions (e.g., `strlen`, `malloc`, etc.).<br>
- Ensure that all functions are working correctly and handle edge cases.<br>
- Create a Makefile to compile your library.<br>
<br>
How to Compile:<br>
<br>
To compile the project, use `make`:<br>
<br>
```bash<br>
make<br>
```<br>
<br>
To clean up object files and binaries:<br>
<br>
```bash<br>
make clean<br>
make fclean<br>
```<br>
<br>
To recompile everything:<br>
<br>
```bash<br>
make re<br>
```<br>
<br>
How to Use:<br>
<br>
Once the library is compiled, you can use the functions in your other C projects.<br>
<br>
Example usage:<br>
<br>
```c<br>
#include "libft.h"<br>
<br>
int main()<br>
{<br>
    char str[] = "Hello, World!";<br>
    ft_putstr(str);  // using a function from libft<br>
    return 0;<br>
}<br>
```<br>
<br>
Key Concepts:<br>
<br>
- Implementing your own utility functions in C.<br>
- Understanding how the standard library functions are built.<br>
- Memory management and string manipulation in C.<br>
<br>
Notes:<br>
<br>
- Focus on optimizing your functions for efficiency.<br>
- Pay attention to edge cases, such as null pointers or empty strings.<br>
- The project emphasizes building a strong understanding of C programming basics.<br>
<br>
Good luck and have fun coding!<br>
