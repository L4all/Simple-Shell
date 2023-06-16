# Simple Shell Project

*Welcome to our Simple Shell project! This project was developed by Abiodun Adekunle and Benjamin Usman as part of the Alx Africa and Holberton School curriculum. The Simple Shell is a command-line interpreter that allows users to execute commands, interact with the operating system, and perform various tasks.*

## Description

*The Simple Shell project is designed to replicate some of the functionalities of the UNIX shell, such as executing commands, handling I/O redirection, and managing processes. It provides a command-line interface where users can input commands, which are then executed by the shell.*

## Features

Our Simple Shell implementation includes the following features:

- Command execution: The shell is capable of executing commands entered by the user.
- Command line editing: Basic line editing features like navigating with arrow keys, deleting characters, and inserting text are supported.
- PATH resolution: The shell searches for executable commands in the directories listed in the PATH environment variable.
- Exit command: Users can exit the shell by typing the `exit` command.
- Single command execution: The shell can execute single command at a time.
- Multiple commands execution: Users can run multiple commands in a single line, separated by semicolons.
- Background execution: Commands can be executed in the background by appending the `&` symbol at the end of the command.
- I/O redirection: Input and output can be redirected using the `<` and `>` symbols, respectively.

## Getting Started

To get started with our Simple Shell project, follow these steps:

1. Clone the repository:

   ```
   $ git clone https://github.com/L4all/simple-shell.git
   ```

2. Compile the source code:

   ```
   $ gcc -Wall -Werror -Wextra -pedantic *.c -o shell
   ```

3. Run the shell:

   ```
   $ ./shell
   ```

4. Start entering commands and experimenting with the features of the shell!

## Usage

Once the shell is running, you can start entering commands. Here are some examples:

- Execute a command:
  ```
  $ ls
  ```

- Execute a command in the background:
  ```
  $ sleep 10 &
  ```

- Execute multiple commands:
  ```
  $ ls ; echo "Hello, World!"
  ```

- Redirect input from a file:
  ```
  $ ./shell < input.txt
  ```

- Redirect output to a file:
  ```
  $ ls > output.txt
  ```

- Exit the shell:
  ```
  $ exit
  ```

## Documentation

For detailed documentation on the Simple Shell project, please refer to the comments within the source code files. They provide explanations and descriptions of the various functions and components of the shell.

## Authors

- Abiodun Adekunle(contributor)
- Benjamin Usman

## License

This project is licensed under the MIT License. See the `LICENSE` file for more information.

## Acknowledgments

We would like to express our gratitude to  alx_africa and Holberton School for providing us with the opportunity to work on this project and improve our understanding of systems programming. Additionally, we would like to thank our classmates and mentors for their support and guidance throughout the development process.
