# Customised Virtual File System (CVFS)

## Project Overview

This project is a **Customised Virtual File System (CVFS)** implemented in **C programming**, designed to simulate the core functionality of the **Linux File System**.

It provides a **custom shell interface** through which users can interact with the virtual file system using Linux-like commands. The project demonstrates practical implementation of **system calls, file handling, memory management, and operating system internals**. 

---

##  Key Features

### Custom Shell Interface

* Interactive command-line interface
* Supports Linux-like commands:

  * `create`
  * `open`
  * `read`
  * `write`
  * `ls`
  * `rm`
* Provides a real-time virtual file system environment

---

### System Call Simulation

* Implementation of core Linux system calls:

  * `open()`
  * `read()`
  * `write()`
  * `lseek()`
  * `close()`
  * `rm()`
* Built entirely using **C language** to mimic OS-level behavior 

---

### File System Data Structures

The project internally manages file operations using:

* Incore Inode Table
* File Table
* UAREA (User Area)
* User File Descriptor Table

These structures simulate how actual operating systems manage files internally. 

---

### Platform Independent

* Works independently of the underlying OS
* Simulates Linux-like file system behavior on any platform

---

### Database-like Functionality

* Structured file handling system
* Acts as a lightweight file-based database layer

---

## Learning Outcomes

Through this project, you gain:

* Deep understanding of **Linux File System Internals**
* Knowledge of **OS-level data structures** (inode, file tables, UAREA)
* Strong foundation in **System Programming using C**
* Experience with **Shell Design and Command Interpreter**
* Exposure to **low-level logic building for OS environments** 

---

## Technologies Used

* **C Programming Language**
* System Programming Concepts
* File Handling & Memory Management
* Operating System Concepts

---

## How to Run

### Compile the Program

```bash id="k2n9s1"
gcc CVFS.c -o Myexe
```

### Run the Executable

```bash id="p9x1rt"
./Myexe
```

---
## Internal Architecture (Conceptual)

* Custom shell parses user commands
* Commands mapped to system call functions
* Data structures manage file metadata and storage
* File operations handled in memory

---

## Project Objective

The main objective of this project is to **simulate a Linux-like file system environment** and provide hands-on experience in:

* System calls implementation
* File system design
* Low-level programming concepts

---
