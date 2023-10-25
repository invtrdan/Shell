# Shell
A simple implementation of the commonly used command shells.

## The shell can be broken down into the following sections:

### Header Files 
The code includes the standard header files for input/output, process control, signal handling, and file operations.

### Constants
The defined constants include the maximum command line length and the maximum number of command line arguments.

###	Signal Handling
Signal handlers for Ctrl-C (SIGINT) and a timer signal (SIGALRM) are defined.

###	Main Function
The main function is the entry point of the program and contains the main logic for the shell.

###	Prompt Printing
A print_shell_prompt function prints the shell prmpts (including the current working directory).

###	Command Processing Loop
The main processing for user commands.

###	Built-In Commands
Several built-in commands are implemented, such as ‘cd’, ‘pwd’, ‘echo’, ‘exit’, ‘env’, and ‘setenv’. These commands are handles separately from external commands.

###	External Command Execution
For external commands, the code forks a child process, handles input/output redirection, and executes the command.

###	Error handling
The code provides error handling for various system calls and functions.

###	Background Execution
The code allows for background execution of commands using the ‘&’ symbol.

###	Piping
The code supports command piping using the ‘|’ sumbol.

###	Clean-up

