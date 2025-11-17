# Libft

A custom C library re-implementing many of the standard C library (libc) functions, built as a learning project as part of the **42 school** curriculum.

---

## Table of Contents

1. [About](#about)  
2. [Features](#features)  
   - [Part 1 – Standard libc Functions](#part-1-standard-libc-functions)  
   - [Part 2 – Utility Functions](#part-2-utility-functions)  
   - [Bonus – Linked List](#bonus-linked-list)  
3. [Installation & Build](#installation--build)  
4. [Usage](#usage)  
5. [Testing](#testing)  
6. [Contributing](#contributing)  
7. [License](#license)  
8. [Contact](#contact)  

---

## About

This project is a foundational exercise to **rebuild core libc functions** from scratch in C. It helps you deeply understand how memory manipulation, strings, and data structures like linked lists work at a low level.

By writing these functions yourself, you:

- Practice pointer arithmetic and memory management  
- Learn how common C functions are implemented  
- Build a personal library that can be reused in future C projects

The repository is located at: `git@github.com:HamzaLaaz/LIBFT.git`.

---

## Features

### Part 1 – Standard libc Functions

Implemented functions from common C headers:

- **Memory operations**:  
  `ft_memset`, `ft_bzero`, `ft_memcpy`, `ft_memmove`, `ft_memchr`, `ft_memcmp`  
- **String operations**:  
  `ft_strlen`, `ft_strlcpy`, `ft_strlcat`, `ft_strchr`, `ft_strrchr`, `ft_strncmp`, `ft_strnstr`, `ft_strdup`  
- **Character tests**:  
  `ft_isalpha`, `ft_isdigit`, `ft_isalnum`, `ft_isascii`, `ft_isprint`  
- **Character conversion**:  
  `ft_toupper`, `ft_tolower`  
- **Conversion & allocation**:  
  `ft_atoi`, `ft_calloc`

### Part 2 – Utility Functions

These are helper functions that go beyond the standard C library, but are very handy in real programs:

- `ft_substr` — extract a substring  
- `ft_strjoin` — join two strings  
- `ft_strtrim` — trim characters from start/end  
- `ft_split` — split a string by a delimiter  
- `ft_itoa` — convert integer to string  
- `ft_strmapi` / `ft_striteri` — apply a function to each character  
- File descriptor output: `ft_putchar_fd`, `ft_putstr_fd`, `ft_putendl_fd`, `ft_putnbr_fd`

### Bonus – Linked List

A simple singly-linked list implementation using a `t_list` struct, with functions:

- `ft_lstnew`, `ft_lstadd_front`  
- `ft_lstsize`, `ft_lstlast`  
- `ft_lstadd_back`, `ft_lstdelone`, `ft_lstclear`  
- `ft_lstiter`, `ft_lstmap`

---

## Installation & Build

1. Clone the repository:  
   ```bash
   git clone git@github.com:HamzaLaaz/LIBFT.git
   cd LIBFT

