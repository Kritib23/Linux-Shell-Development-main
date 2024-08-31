
# Custom Linux Shell

## Overview
This project involves the development of a custom shell that operates above the Linux kernel. The shell is designed to provide an enhanced user experience with optimized performance and advanced functionalities. Key features include efficient process management, parallel command execution, and an extensive command history system.

## Features
- **User-Oriented Design**: An intuitive interface aimed at improving the user experience.
- **Efficient Process Management**: Process groups and signal handlers ensure synchronized execution of child processes.
- **Pipeline-Based Architecture**: Supports parallel command execution with integrated file lock checks.
- **Command History & Editing**: Incorporates command history and editing functionalities using the termios library.

## Technical Details
- **Process Groups**: Group related tasks for efficient management and control.
- **Signal Handlers**: Monitor and synchronize child processes to ensure seamless execution.
- **Syscalls**: Facilitate inter-process communication and manage file locks during parallel execution.
- **Termios Integration**: Provides advanced command history and editing features.


## This project was made by Kriti Bhardwaj, Vinod Meena, Nirbhay Kumar and Sonu Yadav