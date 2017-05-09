# Unix Shell
![alt tag](https://raw.githubusercontent.com/Denisolt/Unix_Shell/master/shell.png)</br>
## Project Scope:
Unix Shell based on the tutorial of Stephen Brennan
This is a very basic implementation that consists of:
- read
- parse
- fork
- exec
- wait

## Limitations:
Limitation include:
- Commands must be on a single line.
- Arguments must be separated by whitespace.
- No quoting arguments or escaping whitespace.
- No piping or redirection.
- Only builtins are: cd, help, exit.

## Execution:
```bash
git clone https://github.com/Denisolt/Unix_Shell.git
cd Unix_Shell-master

#compile the program
gcc -o main main.c

#run it
./main
```
Credits to Stephen Brennan once again for amazing tutorial
