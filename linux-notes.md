\# Linux Notes



\## Basic Commands



\### ls

Lists files and directories.



\### ls -a

Lists all files including hidden files.



\### cd

Changes directory.



Example:

```bash

cd inhere

```



\### cat

Displays contents of a file.



Example:

```bash

cat readme

```



\### pwd

Shows current working directory.



\### file

Shows file type information.



Example:

```bash

file ./\*

```



\### find

Searches for files and directories.



Example:

```bash

find . -type f -size 1033c ! -executable

```



\### ssh

Connects to a remote machine securely.



Example:

```bash

ssh bandit0@bandit.labs.overthewire.org -p 2220

```



\### exit

Closes SSH session or terminal shell.



\---



\## Concepts Learned



\### Hidden Files

Files starting with `.` are hidden in Linux.



\### Escaping Spaces

Use quotes or backslashes for filenames with spaces.



Example:

```bash

cat "./file name"

```



\### Current Directory

`./` refers to current directory.



\### Input Redirection

`<` is input redirection operator, not placeholder text.



\### stderr Redirection

`2>/dev/null` hides error messages.

