# libft – A Custom Standard Library

`libft` is a personal implementation of essential functions from the C standard library. It provides core functionality for string manipulation, memory operations, character classification, and more — making it a foundational utility library for C projects.


## Libft Function Table

| **Category**           | **Function**            | **Description** |
|------------------------|-------------------------|-----------------|
| **Character (CTYPE)**  | `ft_isalpha`            | Check if character is alphabetic |
|                        | `ft_isdigit`            | Check if character is a digit |
|                        | `ft_isalnum`            | Check if character is alphanumeric |
|                        | `ft_isascii`            | Check if character is an ASCII value |
|                        | `ft_isprint`            | Check if character is printable |
|                        | `ft_toupper`            | Convert character to uppercase |
|                        | `ft_tolower`            | Convert character to lowercase |
| **Memory**             | `ft_memset`             | Fill memory with a constant byte |
|                        | `ft_memcpy`             | Copy memory area |
|                        | `ft_memmove`            | Copy memory area (handles overlap) |
|                        | `ft_memchr`             | Locate byte in memory |
|                        | `ft_memcmp`             | Compare memory areas |
|                        | `ft_bzero`              | Zero out memory |
|                        | `ft_calloc`             | Allocate and zero-initialize memory |
| **String (Basic)**     | `ft_strlen`             | Get length of string |
|                        | `ft_strdup`             | Duplicate a string |
|                        | `ft_strchr`             | Locate first occurrence of character |
|                        | `ft_strrchr`            | Locate last occurrence of character |
|                        | `ft_strncmp`            | Compare strings up to `n` characters |
|                        | `ft_strnstr`            | Search for substring within length |
|                        | `ft_strlcpy`            | Copy string with size limit |
|                        | `ft_strlcat`            | Concatenate strings with size limit |
| **String (Advanced)**  | `ft_strjoin`            | Join two strings into a new one |
|                        | `ft_strtrim`            | Trim characters from both ends |
|                        | `ft_substr`             | Extract substring |
|                        | `ft_split`              | Split string by delimiter |
|                        | `ft_striteri`           | Apply function to each character (in-place) |
|                        | `ft_strmapi`            | Map function over string (returns new string) |
|                        | `ft_strs_free`          | Free array of strings |
| **Conversion**         | `ft_atoi`               | Convert string to integer |
|                        | `ft_itoa`               | Convert integer to string |
| **Output (Stream)**    | `ft_putchar_fd`         | Write character to file descriptor |
|                        | `ft_putstr_fd`          | Write string to file descriptor |
|                        | `ft_putendl_fd`         | Write string + newline to file descriptor |
|                        | `ft_putnbr_fd`          | Write integer to file descriptor |



## Build & Usage

To use `libft` in your project:

```
cc yourfile.c -L. -lft -I. -o your_program
```

---

## Debug Mode

If `DEBUG` is defined, additional headers like `<stdio.h>` and `<string.h>` will be included for easier debugging.
