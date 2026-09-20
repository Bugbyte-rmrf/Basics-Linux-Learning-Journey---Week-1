# Skill-Pods Cohort -1
# Basics-Linux-Learning-Journey---Week-1

## 1. Introduction
This week, I started on learning the basic for linus, just like any beginner. My goal was to dive into the command line to understand how the system works behind the scenes. This gave me appreciation of how the process other than only relying on graphical user  interface (GUI).

## My Learning Environment

I performed the practical exercises using a Linux installation on my computer. I used the terminal to practice the commands and observe their results directly.

## 2. What I Learned About Linux
One of my first important discoveries was that "Linux" technically refers only to the kernel, while a complete Linux operating system normally combines this kernel with other software, including GNU tools. The kernel acts as the central controller responsible for managing the functioning of the entire system. 

I also learned about distributions (or "distros"). A distribution packages the Linux kernel together with utilities, management tools, applications, and mechanisms for installing and updating software, making it ready to use out of the box.

## 3. Understanding the CLI (Command Line Interface)
The terminal provides the CLI environment, while the "shell" acts as the interpreter. It reads what you type and passes those instructions to the operating system. 

Here is a visual representation of how this interaction works:

The terminal provides the CLI environment, while the "shell" acts as the interpreter—it reads what you type and passes those instructions to the operating system. 

Here is a visual representation of how this interaction works:

```text
               Beginner
                │
                │ type commands
                ▼
        ┌──────────────┐
        │   Terminal   │
        └──────┬───────┘
                │
                ▼
        ┌──────────────┐
        │    Shell     │
        │    (Bash)    │
        └──────┬───────┘
                │
                │ executes instructions
                ▼
        ┌──────────────┐
        │ Linux Kernel │
        └──────┬───────┘
                │
       ┌───────┼────────┐
       ▼       ▼        ▼
      CPU    Memory    Disk
```

In the beginning, the command line felt unfamiliar because there was no graphical menu telling me what to click. Instead, I had to remember commands and type them correctly. However, after some hands-on practice, I started to understand that Linux commands are structured instructions and not random words to memorize.

## 4. Commands I Practiced & Hands-On Work
During my personal study time, I focused on basic system identification, navigation, and file management. Here is a breakdown of the commands I practiced:

| Command | What I learned / Demonstrated |
| :--- | :--- |
| `whoami` | Shows the user currently logged in. |
| `pwd` | Shows the current working directory (where I am located). |
| `ls` | Lists files and directories in my current location. |
| `cd` | Changes the current directory to move around the filesystem. |
| `mkdir` | Creates a new directory (e.g., `mkdir linux-practice`). |
| `touch` | Creates a new, empty file (e.g., `touch notes.txt`). |
| `echo` | Outputs text and can redirect it to write a file (e.g., `echo "My first Linux file" > notes.txt`). |
| `cat` | Displays the contents of a file directly on the screen. |
| `cp` | Copies files from one location/name to another. |
| `mv` | Moves or renames files. |
| `rm` | Deletes a file permanently. |

### Visual Proof of My Hands-on Practice:

**Checking Identity and Exploring the Filesystem:**
<img width="1304" height="169" alt="Linux basics navigation" src="https://github.com/user-attachments/assets/f613a2d2-b9b6-47bf-b4ce-e3a5ecd34630" />


**Creating Directories and Empty Files:**
<img width="1304" height="117" alt="Files   directories created" src="https://github.com/user-attachments/assets/d2cfb90b-7972-409d-9770-835adaa2dd36" />


**Writing to a File and Reading its Contents:**
<img width="1304" height="67" alt="Reading   Writing File" src="https://github.com/user-attachments/assets/34bb4a8d-3954-4398-8ab6-eec74a9a8c29" />


**Copying and Renaming Files:**
<img width="1304" height="93" alt="Copying   renaming file" src="https://github.com/user-attachments/assets/11585e7c-32f3-4150-a555-854aef64f664" />


**Removing a File and Navigating Backwards:**
<img width="1304" height="137" alt="File removed" src="https://github.com/user-attachments/assets/a09fb202-0b71-47bf-aefb-42668e948a98" />


## 5. Package Management
Because I am practicing on a Debian-based system (like Ubuntu), I also explored the package management system. These systems use tools like `dpkg` at a lower level and `apt` as an easier interface for the user. 

I ran the following command to update my system's software lists:
`sudo apt update`

An important principle I learned here is that operations changing the package state require administrative (superuser) privileges, which is why `sudo` is required.

**Updating System Packages:**
<img width="1312" height="54" alt="Package update" src="https://github.com/user-attachments/assets/85728cb7-971e-4df8-bdd7-2cd24563495a" />

<img width="1312" height="114" alt="Results  - Package Update" src="https://github.com/user-attachments/assets/fd95fc16-264c-437d-bb6a-332fd333eda7" />


## 6. Challenges Faced
Transitioning to the CLI came with a few learning curves:
* **Memory:** Remembering specific commands and their required syntax.
* **Concepts:** Understanding the distinct difference between a file and a directory in a text-only view.
* **Navigation:** Keeping track of exactly where I am currently located in the filesystem hierarchy.
* **Permissions:** Understanding why administrative commands require `sudo` and a password to execute safely.

While learning the CLI requires memorizing commands and options, I found that once you understand the basic command structure and filesystem navigation, it becomes a highly productive environment.

## 8. How I Learned
My learning process involved a combination of studying Linux concepts and then practicing them directly in the terminal. The study material helped me understand concepts such as:

* The Linux kernel
* GNU/Linux
* Linux distributions
* Open-source software
* The command-line interface (CLI)
* Shells
* Applications
* Package management
* Security
* Virtualization
* Linux in cloud computing

After learning the concepts, I practiced basic commands in my own Linux environment. This combination of theory and hands-on practice helped me understand the commands much better.

## 7. Key Takeaways / Conclusion
My biggest takeaway is that Linux is about learning an entirely different way of interacting with a computer. Once you understand the command structure and the filesystem hierarchy, the CLI provides precise control, incredible speed, and an open space for automation through scripting compared to a traditional GUI.
