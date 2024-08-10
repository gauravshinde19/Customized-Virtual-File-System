# Customized Virtual File System (CVFS)

## Overview
This project implements a **CVFS** (Customized Virtual File System) in C++ using C language System programming. The file `CVFS.cpp` contains the core logic for handling the virtual file system operations, including creating, managing, and manipulating files within the virtual environment.

- This project provides all functionality to the user which is same as linux file system.
- It proveides necessary commands, system calls implementations of the file systems through customised shell.
- In this project we implement all necessary data structures of the file systems. Like Incore Inode Table, File table, UAREA, User File Descriptr Table.
- Using this project we can use every system level functionality of linux os on any other os platform.

## Features
- **Technology Used**: system programming using C.
- **User Interface**: Command Line Interface (CLI).
- **Virtual File System**: Manage files and directories in a virtual environment.
- **File Operations**: Create, read, update, and delete files.
- **Directory Operations**: Create and manage files.
- **Custom Implementation**: Designed without relying on external libraries.

## Getting Started

### Prerequisites
To compile and run this project, you need:
- A C++ compiler (e.g., GCC)
- A terminal or command prompt

### How to Compile and Run
1. Compile the source code:
    ```bash
    g++ -o cvfs.cpp Myexe.exe
    ```

2. Run the program:
    ```bash
    Myexe.exe
    ```

## LICENSE
This project is licensed under the MIT License - see the `LICENSE` file for details.
