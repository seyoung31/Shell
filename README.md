# Shell
## Overview
In Fall 2024, I developed a POSIX-compliant shell for [CSCI0330](https://cs0330-fall2024.github.io/). This was a 1.5 month long project and detailed description about the project can be found [here](https://docs.google.com/document/d/1JTB8Yy9qAqghfPRzMMI4eDg_jNIpQ5q87PunVZaYKko/edit?tab=t.0). The main components of the shell is as follows: 
- **Job Control System**: Supports managing foreground and background processes, including launching, suspending, resuming, and terminating jobs using signals.
- **Signal Handling**: Implements signal forwarding for foreground jobs and ignores specific signals for background processes, ensuring proper process interaction and control.
- **Job Management**: Maintains a job list to track process states (running, stopped, terminated) with built-in commands for listing, updating, and removing jobs.
- **Reaping Processes**: Utilizes waitpid() to handle and clean up terminated or stopped processes, printing informative messages based on process state changes.
- **Foreground and Background Execution**: Executes commands in the foreground or background based on user input, with dynamic process group handling for signal delivery and terminal control.

In accordance with Brown University's Academic Code, this repository does not include any specific code implementation of Shell. If you are a potential employer interested in reviewing the code, please feel free to email me at seyoung_jang@brown.edu.
