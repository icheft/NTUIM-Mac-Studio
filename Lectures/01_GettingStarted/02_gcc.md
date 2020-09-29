# `g++` Cheatsheet for Mac

The simplest way to invoke the g++ compiler. Compiles (and links) `file.cpp` to produce an executable named "`executable`".
```sh
g++ file.cpp -o executable
```

Compiles each fileX.cpp file into an (unlinked) object file named `fileX.o`.
```sh
g++ -c file1.cpp file2.cpp ... fileN.cpp
```

Links the listed .o files to produce an executable named "executable".
```sh
g++ file1.o file2.o ... fileN.o -o executable
```

<hr>
Basically, we will only use the first one:

```sh
g++ -std=c++11 file.cpp -o executable
```

Here we add `-std=c++11` to ensure that we are using `c++11` standards (as mentioned in class).

Or alternatively, we can use `make`:
```sh
make file
```

To execute:
```sh
./executable
```

### Terminal Shortcuts You Might Find Helpful
| Key/Command | Description |
| ----------- | ----------- |
| Ctrl + C   | Kill whatever you are running.  Also clears everything on current line |
| Ctrl + D   | Exit the current shell when no process is running, or send EOF to a the running process |
| Tab  | Auto-complete files and folder names |

We'll talk about `makefile` in future lessons.
