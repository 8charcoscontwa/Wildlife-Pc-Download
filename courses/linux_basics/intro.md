# Introduction

## Prerequisites

- Experience of working on any operating systems like Windows, Linux or Mac
- Basics of operating system

## What to expect from this course

This course is divided into three parts. In the first part, we will cover the
fundamentals of linux operating systems. We will talk about linux architecture,
linux distributions and uses of linux operating systems. We will also talk about
difference between GUI and CLI.

In the second part, we will study about some of the basic commands that are used
in linux. We will focus on commands used for navigating file system, commands used
for manipulating files, commands used for viewing files, I/O redirection etc.

In the third part, we will study about linux system administration. In this part, we
will focus on day to day tasks performed by linux admins like managing users/groups,
managing file permissions, monitoring system performance, log files etc.

In the second and third part, we will be taking examples to understand the concepts.

## What is not covered under this course

We are not covering advanced linux commands and bash scripting in this
course. We will also not be covering linux internals. 

## Course Content

### Table of Contents

The following topics has been covered in this course:

- Introduction to Linux
    - (What are Linux Operating Systems)[https://linkedin.github.io/school-of-sre/linux_basics/intro/#what-are-linux-operating-systems]
    - (Linux Distributions)[https://linkedin.github.io/school-of-sre/linux_basics/intro/#what-are-popular-linux-distributions]
    - (Uses of Linux Operating Systems)[https://linkedin.github.io/school-of-sre/linux_basics/intro/#uses-of-linux-operating-systems]
    - (Linux Architecture)[https://linkedin.github.io/school-of-sre/linux_basics/intro/#linux-architecture]
    - (GUI vs CLI)[https://linkedin.github.io/school-of-sre/linux_basics/intro/#graphical-user-interface-gui-vs-command-line-interface-cli]
- (Command Line Basics)[https://linkedin.github.io/school-of-sre/linux_basics/command_line_basics/]
    - (Navigating File System)[https://linkedin.github.io/school-of-sre/linux_basics/command_line_basics/#commands-for-navigating-the-file-system]
    - (Manipulating Files)[https://linkedin.github.io/school-of-sre/linux_basics/command_line_basics/#commands-for-manipulating-files]
    - (Viewing Files)[https://linkedin.github.io/school-of-sre/linux_basics/command_line_basics/#commands-for-viewing-files]
    - (Text Processing Commands)[https://linkedin.github.io/school-of-sre/linux_basics/command_line_basics/#text-processing-commands]
    - (I/O Redirection)[https://linkedin.github.io/school-of-sre/linux_basics/command_line_basics/#io-redirection]
- (Linux system administration)[https://linkedin.github.io/school-of-sre/linux_basics/linux_server_administration/]
    - (User/Groups management)[https://linkedin.github.io/school-of-sre/linux_basics/linux_server_administration/#usergroup-management-in-linux]
    - (Superuser in Linux)[https://linkedin.github.io/school-of-sre/linux_basics/linux_server_administration/#becoming-a-superuser-in-linux]
    - (File Permissions)[https://linkedin.github.io/school-of-sre/linux_basics/linux_server_administration/#file-permissions-in-linux]
    - (SSH Command)[https://linkedin.github.io/school-of-sre/linux_basics/linux_server_administration/#ssh-command]
    - (Package Management)[https://linkedin.github.io/school-of-sre/linux_basics/linux_server_administration/#package-management]
    - (Process Management)[https://linkedin.github.io/school-of-sre/linux_basics/linux_server_administration/#process-management]
    - (Memory Management)[https://linkedin.github.io/school-of-sre/linux_basics/linux_server_administration/#memory-management]
    - (Daemons and Systemd)[https://linkedin.github.io/school-of-sre/linux_basics/linux_server_administration/#daemons]
    - (Logs)[https://linkedin.github.io/school-of-sre/linux_basics/linux_server_administration/#logs]


## What are Linux operating systems

Most of us will be familiar with the windows operating system which is
used in more than 75% of the personal computers. The windows operating systems
are based on windows NT kernel. A kernel is the most important part of
an operating system which performs important functions like process
management, memory management, filesystem management etc.

Linux operating systems are based on the Linux kernel. A linux based
operating system will consist of linux kernel, GUI/CLI, system libraries
and system utilities. The Linux kernel was independently developed and
released by Linus Torvalds. The linux kernel is free and open-source -
[https://github.com/torvalds/linux](https://github.com/torvalds/linux)

History of Linux -
[https://en.wikipedia.org/wiki/History_of_Linux](https://en.wikipedia.org/wiki/History_of_Linux)

## What are popular Linux distributions

A linux distribution(distro) is an operating system that is based on
the linux kernel and a package management system. A package management
system consists of tools that helps in installing, upgrading,
configuring and removing softwares on the operating system.

Softwares are usually adopted to a distribution and are packaged in a
distro specific format. These packages are available through a distro
specific repository. Packages are installed and managed in the operating
system by a package manager.

**List of popular Linux distributions:**

- Fedora

- Ubuntu

- Debian

- Centos

- Red Hat Enterprise Linux

- Suse

- Arch Linux


| Packaging systems      | Distributions                              | Package manager
| ---------------------- | ------------------------------------------ | -----------------
| Debian style (.deb)    |   Debian, Ubuntu                          |   APT
| Red Hat style (.rpm)   |   Fedora, CentOS, Red Hat Enterprise Linux |  YUM

## Linux Architecture

![](/images/linux/commands/image25.png)

- The Linux kernel is monolithic in nature.

- System calls are used to interact with the linux kernel space.

- Kernel code can only be executed in the kernel mode. Non-kernel code is executed in the user mode.

- Device drivers are used to communicate with the hardware devices.

## Uses of Linux Operating Systems

Operating system based on linux kernel are widely used in:

- Personal computers

- Servers

- Mobile phones - Android is based on linux operating system

- Embedded devices - watches, televisions, traffic lights etc

- Satelites

- Network devices - routers, switches etc.

## Graphical user interface (GUI) vs Command line interface (CLI)

A user interacts with a computer with the help of user interfaces. The
user interface can be either GUI or CLI.

Graphical user interface allows a user to interact with the computer
using graphics such as icons and images. When a user clicks on an icon
to open an application on a computer, he or she is actually using the
GUI. It's easy to perform tasks using GUI.

Command line interface allows a user to interact with the computer using
commands. A user types the command in a terminal and the system helps in
executing these commands. A new user with experience on GUI may find it 
difficult to interact with CLI as he/she needs to be aware of the commands
to perform a particular operation.

## Shell vs Terminal

Shell is a program that takes command or a group of commands from the
users and gives them to the operating system for processing. Shell is an
example of command line interface. Bash is one of the most popular shell
programs available on linux servers. Other popular shell programs are
zsh, ksh and tcsh.

Terminal is a program that opens a window and lets you interact with the
shell. Some popular examples of terminals are gnome-terminal, xterm,
konsole etc.

Linux users do use the terms shell, terminal, prompt, console etc.
interchangeably. In simple terms, these all refer to a way of taking
commands from the user.