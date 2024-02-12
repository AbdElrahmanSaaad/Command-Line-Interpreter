# Command Line Interpreter (CLI) for your Operating System

This CLI program allows users to execute various file system operations through a command-line interface. Users can enter commands via the keyboard, and the program will parse the input, execute the indicated command, and provide the appropriate output. The program continues accepting commands until the user enters "exit," at which point the CLI terminates.

## Program Structure

The program consists of two major classes: `Parser` and `Terminal`.

### Parser Class

The `Parser` class is responsible for parsing the user input into a command name and arguments.

### Terminal Class

The `Terminal` class contains methods for each supported command and orchestrates the execution of commands based on user input.

## Required Commands

You will choose 12 commands to implement from the following list:

- `echo`: Takes 1 argument and prints it.
- `pwd`: Takes no arguments and prints the current path.
- `cd`: Implements different cases for changing directories.
- `ls`: Lists the contents of the current directory sorted alphabetically.
- `ls -r`: Lists the contents of the current directory in reverse order.
- `mkdir`: Creates directories.
- `rmdir`: Removes directories.
- `touch`: Creates files.
- `cp`: Copies files or directories.
- `cp -r`: Copies directories recursively.
- `rm`: Removes files.
- `cat`: Prints the content of files or concatenates the content of two files.
- `>`: Redirects output to a file (creates or overwrites).
- `>>`: Appends output to a file.

## Notes

- The program should be written in Java.
- Implement the "exit" command to terminate the CLI.
- Handle errors gracefully, such as wrong commands or bad parameters.
- Use built-in functions and predefined classes in Java; not allow to use "exec" to implement commands.


