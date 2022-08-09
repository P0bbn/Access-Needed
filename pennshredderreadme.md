# Penn-Shredder
A simple program to create a shell that restricts the run-time of executed processes. The shell takes input from users via stdin and executes
said input as a new process. If the process exceeds a timeout, it is killed. If a process is killed, the shell prints a menacing message to stdout.

## Installation and Usage
1. Download the repo
2. In the project directory, compile the program using the `make` command. This program was designed to compile using **clang**, not **GCC**.
3. Run the program using the following syntax: `./penn-shredder <user defined timeout period>`. For example, `./penn-shredder 10` would start the program such that if a command takes longer than 10 seconds, a menacing message will be displayed and the program will end.