# General info
This is the repository for the course of Terminal with Platzi, here you will see what I consider to be the most used commands and some examples. But first what is terminal?.. Terminal is an interface in which you can type and execute text based commands, it is the same with shell it just a interface in which you can run commands, programs and shell scripts, because it is an interface there are many **types**  of shell like **bourne shell**, **C shell**, **Zsh** , **Bash** and many other but they are basicaly the same.

## Table of contents
* [General info](#general-info)
* [Technologies](#technologies)
* [Setup](#setup)
* [Commands](#commands)
	
## Technologies
Project is created with:
* WSL Ubuntu 
* Terminal/Zsh
	
## Setup
First you will need to have a linux distribution or have a Mac with the Unix OS.

Then open your favorite shell (Zsh/Bash/...)
## Commands
| Command       | Descripcion   | Example  |
| ------------- |:-------------:| -----:|
| `$ ls`     | Show the folders and files in that path  | `$ ls Home` |
| `$ cd`     | Allow you to change directory      |   `$ cd Proyect` |
| `$ open`     | You can open files with this command      |   `$ open Proyect.app` |
| `$ cp`     | It copies a file into another directory or just copied      |   `$ cp image.png ~/images/test.png` |
| `$ mv`     | It's similar to copie but this one moves it instead of copying   |   `$ cd Proyect` |
| `$ touch` | It can create any kind of file | `$ touch text.txt test.py` |
| `$ cat`     |  I used it to see shorts files | `$ cat test.txt` |
| `$ less`     | Less is the command to navigate in a file  | `$ less text.txt` |
| `$ nano`     | Nano is the text editor I use  | `$ nano text.txt` |
| `$ man`     | This show you the manual of a command  | `$ man touch` |
| `$ pwd`     | This command show you the directory   | `$ pwd` |
| `$ grep`     | This command show you the directory   | `$ grep -i gera text.txt` |
| `$ alias`     |Allows a string to be substitutued for a word when it is used     |   `$ alias cls='clear'` |
| `$ su`     | This command allow you to switch user  | `$ su roman` |
| `$ rm`     | Removes files or directories   | `$ rm myfile.txt` |
| `$ CTRL + Z ` | Pause the current running command   | `$ CTRL + Z` |
| `$ bg`     | This will start last paused command in background  by appending & in command| `$ bg ` `[1]+ tar czf log-backup.tar.gz /var/log &`|
| `$ jobs`     |  Show you a list of all jobs running in backgorund  | `$ rm myfile.txt` |
| `$ fg`     | This will move background coomands to the foreground  | `$ fg 1` |
| ------------- |:-------------:| -----:|
| `$ ; `     | With this you can serialice commands  | `$ cowsay "hola" > text.txt; cat test.txt` |
| `$ &&`     | The well know AND that make sure all steps are made  |  `$ cowsay "hola" > text.txt && cat test.txt` |