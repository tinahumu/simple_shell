# **THShell** - Simple Shell :shell: Project

### a Simple Shell written Entirely in C programming Language
A simple UNIX command interpreter written entirely in C.

## Description :speech_balloon:

**THshell** is a simple UNIX command language interpreter that reads commands from either a file or standard input and executes them.

### Invocation :rocket:

Usage: **THshell** [filename]

To invoke **THshell**, compile all `.c` files in the repository and run the resulting executable:

```
gcc -Wall -Werror -Wextra -pedantic -std=gnu89 *.c -o THshell
./THshell
```

**THshell** can be invoked both interactively and non-interactively. If **THshell** is invoked with standard input not connected to a terminal, it reads and executes received commands in order.

Example:
```
$ echo "echo 'hello'" | ./THshell
'hello'
$
```

## Authors :black_nib:

* **Hirwa Jr** **||** [Github](https://github.com/HIRWA13) **|** [Twitter](https://twitter.com/itshirwa) **|** [email](tinahumu@gmail.com)  
* **Umurerwa Tinah** **||** [Github](https://github.com/tinahumu) **|** [Twitter](https://twitter.com/umurerwatinah)**|** [email](tinahum@gmail.com)

