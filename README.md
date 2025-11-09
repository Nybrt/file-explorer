# 🧭 Console File Explorer

A beginner-friendly, console-based **File Explorer** written in **C++17** for Linux.  
This project allows users to navigate and manage files and directories directly from the terminal — similar to common Linux shell commands.

Developed and customized by **Nyayabrat Choudhury**  
`debian@Nyayab:~/file-explorer-main/file-explorer$`

---

## 🚀 Features
- `ls`, `cd`, `pwd` — Basic directory navigation  
- `mkdir`, `touch` — Create folders and files  
- `cp`, `mv`, `rm (-r)` — Copy, move, and delete (with recursion)  
- `chmod` — Change permissions using octal input (e.g., 755)  
- `search` — Find files/folders recursively by name  
- `info` — Display file size, type, and permissions  
- `clear`, `help`, `exit` — Utility commands  
- Simple, interactive command prompt for efficient file management  

---

## 🛠️ Requirements
- Linux environment (or WSL on Windows)
- **g++** supporting C++17 or higher (e.g., g++ 8+)
- Basic command-line knowledge

---

## ⚙️ Build Instructions

Clone or download this repository, then open a terminal in the project root folder:

```bash
make

This will compile and create an executable file named: file-explorer

To clean build artifacts:

make clean

▶️ Run the Application

Run the explorer from your terminal:

./file-explorer

You’ll see:

Console File Explorer (C++ / Linux)
Type 'help' for commands.
debian@Nyayab:~/file-explorer-main/file-explorer$

💡 Example Usage

debian@Nyayab:~/file-explorer-main/file-explorer$ ls
debian@Nyayab:~/file-explorer-main/file-explorer$ mkdir test
debian@Nyayab:~/file-explorer-main/file-explorer$ cd test
debian@Nyayab:~/file-explorer-main/file-explorer/test$ touch hello.txt
debian@Nyayab:~/file-explorer-main/file-explorer/test$ ls
debian@Nyayab:~/file-explorer-main/file-explorer/test$ info hello.txt
debian@Nyayab:~/file-explorer-main/file-explorer/test$ cd ..
debian@Nyayab:~/file-explorer-main/file-explorer$ rm test -r
debian@Nyayab:~/file-explorer-main/file-explorer$ exit

🧱 Project Structure :

src/
  main.cpp
  explorer.hpp
  explorer.cpp
Makefile
.gitignore
README.md
LICENSE

📄 License

This project is licensed under the MIT License — see the LICENSE file for details.
👨‍💻 Author

Nyayabrat Choudhury
debian@Nyayab:~/file-explorer-main/file-explorer$
Capstone Project – Linux System Programming
