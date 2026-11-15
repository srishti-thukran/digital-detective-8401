## TASK-3.1 Explore your operating system

-->Operating system / system details --> local 27.2.0 Darwin Kernel Version 27.2.0: Wed Oct 14 23:48:06 PDT 2026; root:xnu-13432.41.4~25/RELEASE_ARM64_T8142 arm64
-->Current account identity --> srishtithukran
-->available and used storage --> 349.69 GB available of 494.33 GB

## TASK-3.2 understand processes

1. What is a process?
A process is a program or application that is currently running on a computer. Every running application or background task requires system resources such as CPU and memory.

2. What does the PID column represent?
PID stands for Process Identifier. It is a unique numerical ID assigned to each running process by the operating system. It helps the operating system identify and manage individual processes.

3. Two example of processes that may be running on your computer
root               449   1.2  0.1 488861632  21536   ??  Ss   Fri09AM   9:33.30 /usr/libexec/runningboard
_windowserver      444   0.4  0.6 490896240 108912   ??  Ss   Fri09AM 147:09.85 /System/Library/PrivateFrameworks/SkyLight.framework/Resources/WindowServer -daemon

## TASK-3.3 Understand Path and Permissions

all the files by default have -rw-r--r-- permission that is read and write for owner and read only permission for group and others

## TASK-3.4 Explain operating-system responsibility

| OS responsibility | Your explanation | Example |
|-------------------|------------------|---------|
| Process management | The operating system manages running programs and decides how CPU time is shared between them | Running a web browser and a music player at the same time |
| Memory management | The operating system manages RAM and allocates memory to different programs when needed | Giving memory to a browser when opening multiple tabs |
| Device management | The operating system controls and manages hardware devices connected to the computer | Managing a keyboard, mouse, printer or USB drive |
| File management | The operating system helps create, store, organise, access and delete files and folders | Creating a folder, saving a document and opening it later |
| User interface/shell | The operating system provides a way for users to interact with the computer through graphical interfaces or command-line shells | Using Finder to open files or Terminal to execute commands |
| Security and permissions | The operating system protects files and system resources by controlling who can access or modify them | Requiring a password to log in and using file permissions to restrict access |

----------------------------------------------------------------------------------------

## 1. Command names used 
--> uname -a
--> whoami
--> df -h
--> top -l 1

## 2. Understanding of processes, storage, paths and permissions

A process is a program or application that is currently running on a computer. Each process has a unique Process Identifier (PID), which helps the operating system identify and manage it.

Storage management helps us understand how much disk space is being used and how much is available.

An absolute path specifies the complete location of a file or directory starting from the root directory.
A relative path specifies the location in relation to the current working directory.

File permissions control what actions users can perform on files and directories.

