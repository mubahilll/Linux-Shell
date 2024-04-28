# Simple Shell Program in C

This is a simple shell program implemented in the C programming language. It provides a basic command-line interface where users can execute various commands and perform operations similar to a Linux shell.

## Features

- Supports basic shell commands such as `cd`, `ls`, and `exit`.
- Handles piped commands using the pipe (`|`) symbol. For example, `command1 | command2`.
- Implements a few custom commands:
  - `help`: Displays a help message with information about supported commands.
  - `hello`: Greets the user and provides a brief welcome message.
- Displays the current directory prompt, allowing users to see their current working directory.
- Uses the Readline library for user input handling and command history, providing convenient command-line editing capabilities.

## Requirements

- This program is designed for Linux systems.
- It requires the Readline library to be installed.

## Compilation and Usage

1. Open a terminal and navigate to the directory containing the code files.
2. Compile the code using the following command:
```bash
gcc shell.c -o shell -lreadline
```
4. Run the shell program with the following command:
```bash
./shell
```
4. The shell program will start, and you can enter commands and interact with the shell.

## Supported Commands

The shell program supports a variety of commands commonly found in Linux shells. Some of the supported commands include:

- **Basic Commands:**
- `cd [directory]`: Changes the current working directory. If no directory is specified, it changes to the user's home directory.
- `ls [options] [directory]`: Lists files and directories in the specified directory. Supports options like `-l` (long format) and `-a` (including hidden files).
- `exit`: Exits the shell program.

- **Piped Commands:**
- `command1 | command2`: Executes `command1` and passes its output as input to `command2`. Supports multiple piped commands.

- **Custom Commands:**
- `help`: Displays a help message with information about the supported commands in the shell.
- `hello`: Greets the user and provides a welcome message.

- **Bash Scripting:**
- You can execute Bash scripts within the shell program. Simply provide the path to the Bash script as a command. For example: `./script.sh`.
- Ensure that the Bash script has executable permissions (`chmod +x script.sh`) to run it successfully.

- **Python Scripting:**
- The shell program supports executing Python scripts. To run a Python script, use the `python` or `python3` command followed by the path to the Python script. For example: `python/python3 script.py.
- Ensure that Python is installed on your system and the Python script has the necessary shebang (`#!/usr/bin/env python` or `#!/usr/bin/env python3`) and executable permissions (`chmod +x script.py`).

Please note that this shell program may not support all the advanced features or complex command structures found in full-fledged shells. It is intended as a basic demonstration of shell functionality.

## Known Issues

- The shell program may not handle certain edge cases or complex command structures.
- It does not support advanced features like command history searching or advanced shell scripting.

## Credits

- This shell program is based on the work of [Mubahil, Ahsan, and Zain].


