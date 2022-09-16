(https://img.shields.io/badge/score-125-success)
(https://img.shields.io/badge/language-C-blue)
(https://img.shields.io/badge/bonus-done-red)
# Libft
---
This project is about coding a C library.
It will contain a lot of general purpose functions your programs will rely upon

## Technical considerations
• Declaring global variables is forbidden.
• If you need helper functions to split a more complex function, define them as static
functions. This way, their scope will be limited to the appropriate file.
• Place all your files at the root of your repository.
• Turning in unused files is forbidden.
• Every .c files must compile with the flags -Wall -Wextra -Werror.
• You must use the command ar to create your library. Using the libtool command
is forbidden.
• Your libft.a has to be created at the root of your repository.

## Part 1 - Libc functions
To begin, you must redo a set of functions from the libc. Your functions will have the
same prototypes and implement the same behaviors as the originals. They must comply
with the way they are defined in their man. The only difference will be their names. They
will begin with the ’ft_’ prefix. For instance, strlen becomes ft_strlen.
Some of the functions’ prototypes you have to redo use the ’restrict’
qualifier. This keyword is part of the c99 standard. It is
therefore forbidden to include it in your own prototypes and to
compile your code with the -std=c99 flag.
You must write your own function implementing the following original ones. 
