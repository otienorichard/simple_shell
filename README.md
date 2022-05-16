# Simple Shell
## Table of contents
* [General info](#general-info)
* [Setup](#setup)
* [Usage](#usage)
* [Authors](#authors)

## General info
This simple shell  executes commands via the kernel process.

## Setup
* Clone repository to your local machine
* Compile with the following gcc flags
  * `gcc -Wall -Werror -Wextra -pedantic *.c -o hsh`
* To run the shell in interactive mode, run the executable file
  * `./hsh`
* To run the shell in non-interactive mode, pipe commands to the executable

## Usage
* In interactive mode, commands should be entered in the following format:
  * `[command][argurments]`
* This Simple Shell is capable of handling these built-in commands:
  * `exit`
  * `^C`
  * `env`
  * `cd`
* The Simple Shell can also execute any command found in $PATH

## Examples
* Interactive mode
  * `coolbean$ ls -l -a`
* Non-interactive mode
  * `echo ls -l -a | ./hsh`

## Authors
This Simple Shell was written by Kennedy Kiragu Maina and Richard Otieno Ouma.
