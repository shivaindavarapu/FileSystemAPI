# 🗂️ In-Memory Virtual Filesystem (Java CLI)

## 🚀 Overview

This is a command-line based **virtual filesystem built entirely in memory using Java**. It mimics a real Linux-like shell and supports navigation, file creation, directory management, and more — all without any disk I/O.

The goal is to **understand how filesystems and shell commands work under the hood**, and to gain hands-on experience with object-oriented design and command interpreters.

---

## 🧾 Problem Statement

Design and implement a **fully in-memory virtual filesystem** that supports standard shell-like commands to manipulate directories and files.

---

## ✅ Supported Features (Phase-wise)

| Command                  | Description                                                                 |
|--------------------------|-----------------------------------------------------------------------------|
| `mkdir <dir>`            | Create a new directory in the current working directory.                   |
| `pwd`                    | Print the full path from root to the current working directory.             |
| `cd <path>`              | Change the current working directory. Supports absolute, relative, `..`, `/`. |
| `ls`                     | List all directories and files in the current directory.                   |
| `tree`                   | Recursively display the directory structure starting from the current dir. |
| `touch <filename>`       | Create a new empty file.                                                    |
| `write <filename> <text>`| Write or overwrite text to a file.                                          |
| `cat <filename>`         | Display the content of a file.                                              |
| `rm <name>`              | Delete a file or directory (recursively if it's a folder).                 |
| `exit`                   | Quit the virtual filesystem shell.                                          |

---
