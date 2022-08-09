# Penn-Shell
A simple shell program to take user input and redirect it using CLI arguments. Input is redirected either to a stdout file or to another process using pipelining.
This program was designed using a customized Ubuntu VM.

## Installation and Use
1. Download the repository.
2. In the project directory, execute the `make` command. This project was designed to be compiled using **clang**. Using **GCC** may not work
3. To start the program, run `./penn-sh`.
4. Apply your own redirect commands to test the functionality. The program **cannot** handle multiple redirects.
