# Simple Shell Project

****
## Table of contents
 - **What is the shell?**
 - **About this project**
 - **Essential Functionalities of the Simple Shell**
 - **Technologies & Tools: Computer**
 - **USAGE**
 - **Example of Usage**
 - **Bugs**
 - **AUTHORS**
 ****

## What is the shell?
The shell is a program that takes commands from the keyboard via the terminal, and gives them to the operating system to perform.\
**To better understand how the shell actually works, you can read our [Article].**

## About this project
This project is a simple version of the linux shell made after taking part of the "Low-level programming & Algorithm - Linux and Unix system programming" projects.
It is created using the **C programming Language** and it can do many functionalities that a real shell does.

## Essential Functionalities of the Simple Shell:
> Displays a prompt "╰═┅═━–〈hezron_shell╼┈➤$" and waits for user input.\
> Runs all commands of type "executable program" (ls and /bin/ls).\
> Handles commands with arguments.\
> Handles the PATH global variable.\
> Handles The EOF (End Of File) condition.\
> Handles the Ctrl + C signal -> It doesn't exit the shell

****
## Technologies & Tools:computer:

![Ubuntu](https://img.shields.io/badge/≡-Ubuntu-E95420?&style=flat-square&logo=Ubuntu&labelColor=282828)
![Git](https://img.shields.io/badge/≡-Git-F05032?logo=git&style=flat-square&labelColor=282828)
![GNU_Bash](https://img.shields.io/badge/≡-GNU_Bash-4EAA25?logo=GNU-Bash&style=flat-square&labelColor=282828)
![Vim](https://img.shields.io/badge/≡-Vim-019733?logo=Vim&style=flat-square&logoColor=019733&labelColor=282828)
![Vagrant](https://img.shields.io/badge/≡-Vagrant-1563FF?logo=Vagrant&style=flat-square&logoColor=1563FF&labelColor=282828)
![C](https://img.shields.io/badge/≡-C-A8B9CC?logo=C&style=flat-square&labelColor=282828)
![GNU_Emacs](https://img.shields.io/badge/≡-GNU_Emacs-7F5AB6?logo=GNU-Emacs&style=flat-square&labelColor=282828)
![GitHub](https://img.shields.io/badge/≡-GitHub-181717?logo=GitHub&style=flat-square&labelColor=282828)

---

### Clone repo using HTTPS
```
$ git clone https://github.com/Hezron-Simumba/simple_shell.git
```
---

You can compile the files using this command to check that there are no errors:
```
$ gcc -Wall -pedantic -Werror Wextra *.c -o hsh
```

## USAGE
You can try my shell by following these steps:
> **Step 1:** Clone my repository using this command, (you need to have git installed on your machine first)
````
git clone https://github.com/Hezron-Simumba/simple_shell.git
````
> **Step 2:** Change directory to simple_shell:
````
cd simple_shell
````
> **Step 3:** Compile the C files in this way:
````
gcc -Wall -Werror -Wextra -pedantic *.c -o hez
````
> **Step 4:** Run the shell
````
./hez
````
 **You will see the bellow command prompt interface awaiting for you to input the command**
````
╰═┅═━–〈hezron_shell╼┈➤$
````
**Exiting the shell**
When you want to exit the shell, you can use one of the following methods:
> **1: Type the command "exit"**
````
exit
````
> **2: Press on Ctrl + D**

## Example of Usage
````
ubunto@ubuntu:~/Hezron/simple_shell$ gcc -Wall -Wextra -Werror -pedantic *.c -o hez
ubunto@ubuntu:~//simple_shell$ ./hez
#╰═┅═━–〈hezron_shell╼┈➤$ echo Hezron
Hezron
#╰═┅═━–〈hezron_shell╼┈➤$ ls
Lists files in a directory
#╰═┅═━–〈hezron_shell╼┈➤$
#╰═┅═━–〈hezron_shell╼┈➤$ ls -l
This command shows files and file permissions, e.t.c
#╰═┅═━–〈hezron_shell╼┈➤$ exit
This command exits the shell
ubunto@ubuntu:~/Hezron/simple_shell$
````
---

## Bugs
No known Bugs.

----
## Authors
* **HEZRON SIMUMBA** - [Hezron-Simumba](https://github.com/Hezron-Simumba)
  [<img src="https://img.shields.io/badge/Portfolio-20d6fe.svg?&style=plastic"/>](https://hezron-simumba.github.io/)
[<img src="https://img.shields.io/badge/Twitter-1DA1F2.svg?&style=plastic&logo=twitter&logoColor=white"/>](https://twitter.com/Hezron_Simumba)
[<img src="https://img.shields.io/badg/Linkedin-0A66C2.svg?&style=plastic&logo=linkedin&logoColor=white"/>](https://www.linkedin.com/in/hezron-simumba-b1342419a)
[<img src="https://img.shields.io/badge/GitHub-181717.svg?&style=plastic&logo=github&logoColor=white"/>](https://github.com/Hezron-Simumba)

## AUTHOR DESCRIPTION (Hezron Simumba)
 - I'm a Food Process Engineer, Ricoh Printers Service Engineer and a software engineering student at Holberton School(ALX-AFRICA).
  - I have been studying low-level programming, high-level
 programming, system engineering and devops, and web
 stack programming (Front-end & Back-end) using a
 methodology based on peer-learning and projects.
  - I'm curious, adaptable, a fast learner and I love developing my skills.e
