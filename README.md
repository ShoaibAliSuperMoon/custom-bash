# MyShell - Custom Unix Shell in C

## 📝 Overview

`myshell.c` is a custom Unix-like shell built in C that mimics basic behavior of standard shells (like `bash` or `sh`). It supports execution of commands, parallel and sequential execution, I/O redirection, command piping, and basic signal handling.

This project showcases system programming concepts such as process forking, signal handling, inter-process communication, and command parsing—making it ideal for showcasing in your software engineering resume or GitHub portfolio.

---

## 🚀 Features

- 🔧 **Standard Command Execution** – Runs shell commands using `execvp()`.
- 📁 **Directory Change Support** – Handles `cd` with and without path.
- ⚙️ **Parallel Execution** – Run multiple commands using `&&`.
- 📚 **Sequential Execution** – Run multiple commands using `##`.
- 📤 **Output Redirection** – Redirect output to files using `>`.
- 🔗 **Pipes** – Supports piped commands using `|`.
- 🔒 **Signal Handling** – Handles `SIGINT` (Ctrl+C) and `SIGTSTP` (Ctrl+Z) gracefully.
- 🧠 **Manual Input Parsing** – Custom implementation of input tokenization using `strsep()` and `strtok()`.

---

## ⚙️ Compilation

Use GCC to compile:

```bash
gcc myshell.c -o myshell
