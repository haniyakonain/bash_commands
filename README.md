# 💻 TERMINAL & BASH COMMANDS

A quick reference guide for navigating and working with the terminal, Bash commands, and Node.js.

---

## 🚀 Opening the Terminal

- **Shortcut**: `Ctrl + Alt + T`  
Launches the terminal — a command-line interface to interact with your machine.

---

## 🧭 Navigation Commands

| Command         | Description                    |
|-----------------|--------------------------------|
| `pwd`           | Prints the current working directory |
| `cd foldername` | Change into a directory |
| `cd ..`         | Move one folder back |
| `cd ../..`      | Move two folders back |
| `cd path/to/dir`| Navigate using full path |

---

## 📁 File & Directory Management

| Command | Description |
|--------|-------------|
| `ls`               | List files and directories |
| `mkdir foldername` | Create a directory |
| `touch filename`   | Create an empty file |
| `cat filename`     | Display file contents |
| `/` in path        | Used to navigate into nested folders, e.g. `folder1/folder2` |

---

## 📝 File Editing with `vi`

| Command      | Function |
|--------------|----------|
| `vi filename`| Open file in vi editor |
| `i`          | Insert mode |
| `Esc :q!`    | Exit without saving |
| `Esc :wq!`   | Save and exit |

---

## 🛠 File Operations

| Command                      | Description |
|------------------------------|-------------|
| `mv source destination`      | Move or rename a file/folder |
| `cp source destination`      | Copy a file |
| `cp -r source destination`   | Copy a folder recursively |

---

## 🔁 Command Shortcuts

| Shortcut       | Description |
|----------------|-------------|
| ↑ (up arrow)   | Browse previous commands |
| `clear`        | Clears the terminal |
| `Ctrl + C`     | Stop process / Exit current command |

---

## 🟢 Node.js & NPM

| Command                      | Description |
|------------------------------|-------------|
| `nvm`                        | Node Version Manager |
| `node`                       | Start Node.js REPL shell |
| `node filename.js`           | Run a Node.js script |
| `npm install package-name`   | Install a package (e.g., `npm install express`) |

---

## ✅ Example Workflow

```bash
mkdir myproject
cd myproject
touch index.js
vi index.js
node index.js
````

---

## 📘 Notes

* Use `cat`, `vi`, or `node` to interact with files depending on your needs.
* Always double-check file paths when using `mv` or `cp` to avoid accidental data loss.

---




