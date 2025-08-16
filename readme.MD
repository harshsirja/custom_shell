# Custom Shell

A custom Unix-like shell built in C that supports basic command execution,built-in commands, and more.

This project is a custom shell created to understand the inner workings of Unix shells and improve system programming skills. It solves the problem of executing and managing system commands in a simplified environment, ideal for learning. The shell supports command built-in functions, piping, redirection, and custom prompts to enhance user interaction and functionality.

---

## Table of Contents

- [Features](#features)  
- [Getting Started](#getting-started)  
  - [Prerequisites](#prerequisites)  
  - [Setup](#setup)  
- [Usage](#usage)  
---

## Features

- **Built-in Commands**: Implements built-in commands such as `cd`, `pwd`, `echo`, `ls` and many more.
- **Piping and Redirection**: Supports command piping (`|`).

---

## Getting Started

### Prerequisites

Ensure you have the following software installed:

- GCC (C compiler)
---

### Setup

Follow these steps to set up and run the shell:

1. **Clone the repository:**
    a.
   ```bash
    git@github.com:harshsirja/custom_shell.git
2. **Navigate to the project directory:**
    ```bash
    cd custom_shell
3. **Compile the source code:**
    ```bash
    gcc shell.c -o shell
4. **shell**
    ```bash
    ./shell
---

### Usage
1. **How to use custom shell with example**
    ```bash
    $ ./my_shell
    
    shell> ls
    readme.MD
    shell.c

    shell> echo "Hello, World!"
    Hello, World!
---