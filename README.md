# software-vulnerabilities-segfault
Software Vulnerabilities - Segmentation Fault

## What is
Means that an access to a restricted area of memory has occurred. Each program uses a reserved part of the RAM memory, when tries to access to another part of the memory it is called segmentation fault.

#### Vulnerabilities will be programs written in C. First needed is a C compiler in any OS.
### Windows:
MinGW can be downloaded from here https://sourceforge.net/projects/mingw/files/Installer/
Once installed and given an example of program.c :
1.	Open line command (cmd)
2.	Go to MinGM directory \bin
3.	Compile file: ``` gcc.exe -o nameCompiledFile  pathOfFile\program.c ```
4.	nameCompiledFile.exe will be generated in MinGW\bin
5.	Execute file nameCompiledFile.exe

### Linux:
Most of Linux distros have already compiler installed so it is much easier to execute:
1.	Open terminal and write: ``` gcc -o nameCompiledFile nameProgramFile.c ```
If a program that uses threads is going to be executed then compilance should be:
``` gcc -pthread -o nameCompiledFile nameProgramFile.c ```
2.	After compilance, program can be executed:
``` ./nameCompiledFile ```

