#Simple Shell
This is a basic implementation of a shell written in C.

#Features
Can execute basic commands such as ls, pwd, echo, etc.
Can handle command arguments and flags.
Can handle multiple commands on one line separated by ;.
Can handle standard input and output redirection using > and <.
Can handle background processes using &.
#How to use
Compile the code using gcc shell.c -o shell.
Run the compiled binary using ./shell.
The shell prompt will appear, and you can enter commands as you would in a regular shell.
#Limitations
Does not handle pipes (|) or environment variables.
Only supports a limited number of built-in commands.
Error handling is minimal.
#Future Improvements
Add support for pipes and environment variables.
Improve error handling.
Add more built-in commands.
Add support for command history and tab completion.
This shell is for educational purpose and not intended to be used as a production shell.
