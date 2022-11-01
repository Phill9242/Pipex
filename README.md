# Pipex

### In this project we start to go deep at shell behavior.

We must build a program that reproduce the behavior of the pipe ( | ) in Linux Shell.

The program take the follow parameters:

    file1 cmd1 cmd2 file2

"cmd" are the shell commands and "file" are the files that will be used as in file and out file

The errors must be displayed correctly too.

### Examples

In the following parameters:

    in "grep a" "ls -la" out

The program must behaviour like the shell command:

    < in grep a | cmd2 > out


