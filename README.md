What is the shell?
The shell is a program that takes commands from the keyboard via the terminal, and gives them to the os to perform.

About this project :
This project is a simple version of the linux shell made for Holberton School taking part of the "Low-level programming & Algorithm - Linux and Unixsystem programming" projects.
we used c programming language, it can do many functionalities that a real shell does.

Files description :
      AUTHORS -> List of contributors to this repository.
      man_1_simple_shell -> Manual page for the simple_shell.
      shell.h -> Header file.
      shell.c -> main function.
      string.c ->
      	  _putchar -> prints a character.
	  _puts -> prints a string.
	  _strlen -> gives the length of a string.
	  _strdup -> copies a string in a newly allocated memory.
	  concat_all -> concatenates 3 strings in a newly allocated memory.
      line_exec.c ->
          splitstring -> splits a string into an array of words.
	  execute -> executes a command using execve.
	  realloc -> reallocates a memory block.
	  freearv -> frees a 2 dimensional array.
      linkpath.c ->
          _getenv -> returns the value of a global variable.
	  add_node_end -> adds a node in a singly linked list.
	  linkpath -> creates a singly linked list for PATH directories.
	  _which -> finds the pathname of a command.
	  free_list -> frees the linked list of PATH value.
      checkbuild.c -> checks if a command is a build-in command.
      buildin.c ->
          exitt -> handles the exit buildin command.
	  _atoi -> converts a string into an integer.
	  env -> prints the current environment.
	  _setenv -> Initialize a new global variable, or modify an existing one.
	  _unsetenv -> remove a global variable.

List of allowed functions and system calls
     access (man 2 access).
     chdir (man 2 chdir).
     close (man 2 close).
     closedir (man 3 closedir).
     execve (man 2 execve).
     exit (man 3 exit).
     _exit (man 2 _exit).
     fflush (man 3 fflush).
     fork (man 2 fork).
     free (man 3 free).
     getcwd (man 3 getcwd).
     getline (man 3 getline).
     getpid (man 2 getpid).
     isatty (man 3 isatty).
     kill (man 2 kill).
     malloc (man 3 malloc).
     open (man 2 open).
     opendir (man 3 opendir).
     perror (man 3 perror).
     read (man 2 read).
     readdir (man 3 readdir).
     signal (man 2 signal).
     stat (__xstat) (man 2 stat).
     lstat (__lxstat) (man 2 lstat).
     fstat (__fxstat) (man 2 fstat).
     strtok (man 3 strtok).
     wait (man 2 wait).
     waitpid (man 2 waitpid).
     wait3 (man 2 wait3).
     wait4 (man 2 wait4).
     write (man 2 write).