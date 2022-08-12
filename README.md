# SIMPLE SHELL :shell:

## Description :page_with_curl:

This is a simple implementation of a UNIX command line interpreter. The shell can interpret and execute command line arguments read from the standard input. the shell read lines from a file or terminal line which is then interpreted and executed if the command is valid

## Requirements

- All the files are to be compiled on an Ubuntu 14.04 LTS machine with:
  `gcc -Wall -Werror -Wextra -pedantic *.c `
- All files ends end with a new line, with no memory leaks
- All code will use the Betty style. It will be checked using `betty-style.pl` and `betty-doc.pl`
- All code will be tested using the test files in the test folder.
- The simple shell supports most shell commands, such as `cat`, `pwd`,` ls -la` and more.

## Return Value :

The shell returns a value of 0 if the command is valid and the command is executed successfully.

## Output :file_folder:

- The program must have the exact same output as `sh (/bin/sh)` as well as the exact same error output.
- The only difference is when you print an error, the name of the program must be equivalent to the `argv[0]`

## Usage
## list of fucntions and system calls used

```
- access (man 2 access)
- chdir (man 2 chdir)
- close (man 2 close)
- closedir (man 3 closedir)
- execve (man 2 execve)
- exit (man 3 exit)
- _exit (man 2 _exit)
- fflush (man 3 fflush)
- fork (man 2 fork)
- free (man 3 free)
- getcwd (man 3 getcwd)
- getline (man 3 getline)
- isatty (man 3 isatty)
- kill (man 2 kill)
- malloc (man 3 malloc)
- open (man 2 open)
- opendir (man 3 opendir)
- perror (man 3 perror)
- read (man 2 read)
- readdir (man 3 readdir)
- signal (man 2 signal)
- stat (__xstat) (man 2 stat)
- lstat (__lxstat) (man 2 lstat)
- fstat (__fxstat) (man 2 fstat)
- strtok (man 3 strtok)
- wait (man 2 wait)
- waitpid (man 2 waitpid)
- wait3 (man 2 wait3)
- wait4 (man 2 wait4)
- write (man 2 write)

```

## Contributors :two_men_holding_hands:
Oyeniyi Taoheed <oyeniyiemperor@gmail.com>
NaheemahBello <nimabello009@gmail.com>
