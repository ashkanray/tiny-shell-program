# tiny-shell-program - Tiny Shell with Job Control

## Description
tsh is a tiny shell program written in C, featuring job control. It allows users to execute commands in both foreground and background processes, and includes built-in signal handling for interrupts (SIGINT, SIGTSTP) and child process termination (SIGCHLD).

## Installation
Clone the repository.
Navigate to the directory containing tsh.
Compile the code using a C compiler, e.g., gcc -o tsh tsh.c.

## Usage
Run the shell: ./tsh.
Use the shell prompt tsh> to enter commands.
Use ctrl-c to send SIGINT, ctrl-z to send SIGTSTP, and ctrl-d to exit.

## Features
Command execution in foreground and background.
Job control with SIGINT, SIGTSTP, and SIGCHLD handling.
Internal job list to track process IDs (PIDs) and job IDs (JIDs).
