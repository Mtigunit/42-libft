# Libft

## Description
Libft is a library that contains a collection of functions aimed at providing a useful tool for your cursus. It includes implementations of standard C library functions, as well as additional functions that are either not found in the libc or are provided in a different form. This library will serve as a foundation for many of your future projects, allowing you to easily reuse and expand upon these functions.

## Technical Considerations
- Declaring global variables is forbidden to maintain encapsulation and modularity.
- If you need to split a more complex function, define helper functions as static functions within the file where they are used. This limits their scope to the appropriate file.
- All files for the library should be placed at the root of your repository.
- Ensure that you do not turn in any unused files to maintain a clean project structure.
- Every `.c` file in the library must compile without any warnings or errors when using the flags `-Wall`, `-Wextra`, and `-Werror`.
- The library must be created using the `ar` command. The use of the `libtool` command is forbidden.
- The resulting `libft.a` file must be placed at the root of your repository for easy inclusion in future projects.

## Part 1 - Libc Functions
In this part, you need to reimplement a set of functions from the standard C library (libc). Your functions should have the same prototypes and behaviors as the original libc functions but with the prefix 'ft_' added to their names. By implementing these functions yourself, you will gain a deeper understanding of how they work and improve your programming skills.

Some of the functions you need to implement include:
- `ft_isalpha`
- `ft_isdigit`
- `ft_isalnum`
- `ft_isascii`
- `ft_isprint`
- `ft_strlen`
- `ft_memset`
- `ft_bzero`
- `ft_memcpy`
- `ft_memmove`
- `ft_strlcpy`
- `ft_strlcat`
- `ft_toupper`
- `ft_tolower`
- `ft_strchr`
- `ft_strrchr`
- `ft_strncmp`
- `ft_memchr`
- `ft_memcmp`
- `ft_strnstr`
- `ft_atoi`

In addition, you need to implement the following functions using dynamic memory allocation with `malloc`:
- `ft_calloc`
- `ft_strdup`

## Part 2 - Additional Functions
In this part, you need to develop a set of additional functions that are either not found in the libc or are provided in a different form. These functions will enhance the functionality of the library and provide useful tools for future projects.

Some of the additional functions you need to implement include:
- `ft_substr`
- `ft_strjoin`
- `ft_strtrim`
- `ft_split`
- `ft_itoa`
- `ft_strmapi`
- `ft_striteri`
- `ft_putchar_fd`
- `ft_putstr_fd`
- `ft_putendl_fd`
- `ft_putnbr_fd`

These functions will allow you to manipulate strings, perform conversions, iterate over strings, and output text to file descriptors.

## Bonus Part
If you have successfully completed the mandatory part, you have the opportunity to go further and implement additional functions to manipulate linked lists. The necessary structure and functions to manipulate lists are provided, and you should add their appropriate declarations in the `libft.h` header file.

Some of the bonus functions you can implement include:
- `ft_lstnew`
- `ft_lstadd_front`
- `ft_lstsize`
- `ft_lstlast`
- `ft_lstadd_back`
- `ft_lstdelone`
- `ft_lstclear`
- `ft_lstiter`
- `ft_lstmap`

These functions will allow you to create, manipulate, and iterate over linked lists, providing powerful tools for handling dynamic data structures.
