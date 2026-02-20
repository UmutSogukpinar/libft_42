<div align="center">
  <a href="https://github.com/umutsogukpinar/libft">
    <img src="https://github.com/ayogun/42-project-badges/blob/main/badges/libftm.png" alt="LIBFT Logo" width="200">
  </a>

  <h1>LIBFT</h1>

  <p>
    <b

> Reimplementation of essential C standard library functions.

Libft is a foundational project that focuses on recreating commonly used C library functions from scratch. The goal is to deeply understand memory management, string manipulation, and data structures while building a reusable static library for future projects.

---

## Table of Contents

* [Installation](#installation)
* [Usage](#usage)
* [Functions](#functions)

  * [Libc Functions](#libc-functions)
  * [Additional Functions](#additional-functions)
  * [Bonus Part (Linked List)](#bonus-part-linked-list)
* [Compilation Rules](#compilation-rules)
* [Notes](#notes)

---

## Installation

Clone the repository and build the library:

```bash
make
```

This will generate:

```
libft.a
```

Clean object files:

```bash
make clean
```

Remove all generated files:

```bash
make fclean
```

Rebuild everything:

```bash
make re
```

Build bonus part:

```bash
make bonus
```

---

## Usage

Include the header in your project:

```c
#include "libft.h"
```

Compile your program with the library:

```bash
cc main.c -L. -lft -I. -o program
```

---

## Functions

### Libc Functions

* ft_isalpha
* ft_isdigit
* ft_isalnum
* ft_isascii
* ft_isprint
* ft_strlen
* ft_memset
* ft_bzero
* ft_memcpy
* ft_memmove
* ft_strlcpy
* ft_strlcat
* ft_toupper
* ft_tolower
* ft_strchr
* ft_strrchr
* ft_strncmp
* ft_memchr
* ft_memcmp
* ft_strnstr
* ft_atoi
* ft_calloc
* ft_strdup

---

### Additional Functions

* ft_substr
* ft_strjoin
* ft_strtrim
* ft_split
* ft_itoa
* ft_strmapi
* ft_striteri
* ft_putchar_fd
* ft_putstr_fd
* ft_putendl_fd
* ft_putnbr_fd

---

### Bonus Part (Linked List)

The bonus part introduces a simple singly linked list structure:

```c
typedef struct s_list
{
    void            *content;
    struct s_list   *next;
}   t_list;
```

Linked list functions:

* ft_lstnew
* ft_lstadd_front
* ft_lstsize
* ft_lstlast
* ft_lstadd_back
* ft_lstdelone
* ft_lstclear
* ft_lstiter
* ft_lstmap

---

