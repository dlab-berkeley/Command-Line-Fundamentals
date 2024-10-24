## **BASH Command Line Cheat Sheet**

### **Basic Navigation**
| Instruction                       | Command                    |
|----------------------------------------|----------------------------|
| Show current directory            | `pwd`                      |
| List files in current directory   | `ls`                       |
| List all files (including hidden) | `ls -a`                    |
| List files with details (permissions, size) | `ls -l`|
| Change directory                  | `cd directory_name`        |
| Go up one directory               | `cd ..`                    |

### **File and Directory Management**
| Instruction                       | Command                    |
|-----------------------------------|----------------------------|
| Create a new directory            | `mkdir directory_name`     |
| Remove a file                     | `rm file_name`             |
| Remove a directory                | `rm -r directory_name`     |
| Copy a file                       | `cp source_file dest_file` |
| Move or rename a file             | `mv old_name new_name`     |

### **File Viewing & Editing**
| Instruction                       | Command                    |
|-----------------------------------|----------------------------|
| Display file contents             | `cat file_name`            |
| View file with scrolling          | `less file_name`           |
| Display first 10 lines of a file  | `head file_name`           |
| Display last 10 lines of a file   | `tail file_name`           |
| Open a file in text editor (nano) | `nano file_name`           |

### **Search & Filters**
| Instruction                       | Command                    |
|-----------------------------------|----------------------------|
| Search for a pattern in a file    | `grep "pattern" file_name` |
| Find files by name                | `find /path -name "file_name"` |

### **Redirection & Pipes**
| Instruction                       | Command                    |
|-----------------------------------|----------------------------|
| Redirect command output to file   | `command > file_name`      |
| Append command output to file     | `command >> file_name`     |
| Use output of one command as input to another | `command1 `\| `command2`  |

### **System Information**
| Instruction                       | Command                    |
|-----------------------------------|----------------------------|
| Show current username             | `whoami`                   |
| Show current running processes    | `ps`                       |
| Show memory usage                 | `free -h`                  |
| Show disk usage                   | `df -h`                    |
| Show command history              | `history`                  |

### **System Utilities**
| Instruction                       | Command                    |
|-----------------------------------|----------------------------|
| Clear terminal screen             | `clear`                    |
| Show manual for a command         | `man command_name`         |
| Repeat last command               | `!!`                       |

### **Other Useful Commands**
| Instruction                       | Command                    |
|-----------------------------------|----------------------------|
| Create a file with text           | `echo "text" > file_name`  |
| Append text to a file             | `echo "more text" >> file_name` |
| Combine multiple commands         | `command1 && command2`     |

