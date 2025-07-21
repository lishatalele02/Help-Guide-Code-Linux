
# 🐧 Linux Help Guide (Shell Script)

This project is an **interactive Linux Help Guide** written in **Bash**. It provides users with concise help information and examples for commonly used Linux commands across multiple categories such as general purpose, file manipulation, process control, etc.

## 📋 Features

- Menu-driven user interface in the terminal
- Covers **7 categories** of Linux commands:
  1. General Purpose Commands
  2. Basic Commands
  3. File Manipulation Commands
  4. Directory Manipulation Commands
  5. Process Commands
  6. Text Processing Commands
  7. Exit

- Explains command usage, options, and provides real-world examples
- Lightweight and easy to run on any Linux system

## 🚀 How to Use

1. Open a terminal
2. Run the script:

```bash
bash linux_help_guide.sh
```

3. Choose the category and command number to see help details.

## 🗃️ Command Categories & Examples

### 1. General Purpose
- `tty`: Displays terminal file
- `cal`: Shows calendar
- `clear`: Clears the terminal screen
- `date`: Displays current date/time in custom format

### 2. Basic Commands
- `who`, `whoami`, `pwd`, `passwd`

### 3. File Manipulation
- `cp`, `mv`, `rm` (with options like `-r`, `-v`, `-f`)

### 4. Directory Manipulation
- `mkdir`, `rmdir`, `cd`, `dir`, `chmod`

### 5. Process Management
- `ps`, `kill`, `sleep`

### 6. Text Processing
- `grep`, `tr`, `wc`

### 7. Exit
- Closes the script

## 📦 Requirements

- Bash shell (default in Linux)
- No additional dependencies

## 📌 Example

```bash
=============== Linux Help Guide ===============
1. General Purpose Commands
2. Basic Commands
...
Enter your choice [1-7]: 1

General Purpose Commands:
1. tty
2. cal
...
Enter command number [1-4]: 2
Command: cal
Usage: cal [options]
Description: Displays a formatted calendar.
...
```

## 📁 File Structure

```
linux_help_guide.sh       # The main script file
README.md                 # Project documentation
```

## 🛠️ To Do / Improvements

- Add color output for better readability
- Include more categories (networking, system info, etc.)
- Add keyboard shortcuts for faster navigation

## 📝 License

This project is released under the [MIT License](LICENSE).
Feel free to use, modify, and distribute.

---

🔧 Created to help Linux beginners and students learn commands with practical examples.

