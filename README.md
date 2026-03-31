# 🧰 Kernel_Utility_Suite

 Linux command-line utilities built in C using low-level system calls.
---

## 📌 Project Overview

**Kernel_Utility_Suite** is a system programming project that replicates essential Unix/Linux commands using low-level system calls.

It provides hands-on understanding of:
- File handling
- Directory management
- Process-level operations
- Kernel interaction via system calls

---

## ⚙️ Technologies Used

- 🟢 C Programming Language
- 🐧 Linux / Unix OS
- 🔧 GCC Compiler
- 📁 System Calls (`open`, `read`, `write`, `close`, `chdir`, etc.)

---

## ✨ Utilities Implemented

This project includes **13 custom commands**:

| Command | Description |
|--------|------------|
| `catx` | Display file contents |
| `cdx`  | Change directory |
| `lsX`  | List directory contents |
| `cpX`  | Copy files |
| `mvX`  | Move/Rename files |
| `rmX`  | Delete files |
| `pwdX` | Show current directory |
| `touchX` | Create file |
| `statX` | File information |
| `headX` | Show first lines |
| `tailX` | Show last lines |
| `wcX` | Count words/lines |
| `echoX` | Print text |

> ⚠️ Replace/add actual command names if different.

---

## 📂 Project Structure

Kernel_Utility_Suite/
<br>
│
<br>
├── catx.c
<br>
├── cdx.c
<br>
├── lsX.c
<br>
├── cpX.c
<br>
├── mvX.c
<br>
├── rmX.c
<br>
├── pwdX.c
<br>
├── touchX.c
<br>
├── statX.c
<br>
├── headX.c
<br>
├── tailX.c
<br>
├── wcX.c
<br>
├── echoX.c
<br>
└── README.md

---


## ▶️ How to Compile

### Compile each utility separately:

gcc catx.c -o myexe
<br>
gcc cdx.c -o myexe
<br>
gcc lsX.c -o myexe

---

## ▶️ How to Run
./myexe

---

## 📌 Example Usage
### 🔹 View File
./catx demo.txt

### 🔹 Change Directory
./cdx /home/user/Documents





