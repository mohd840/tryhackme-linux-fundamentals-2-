# Linux Fundamentals Part 2 – TryHackMe

This repository contains my notes and commands from completing the **Linux Fundamentals Part 2** room on TryHackMe.

Linux is a fundamental skill for cybersecurity professionals, penetration testers, and system administrators. This room focuses on file manipulation, permissions, processes, and useful commands used in Linux environments.

Platform: TryHackMe  
Room: Linux Fundamentals Part 2

---

## Topics Covered

- File and directory permissions
- Changing permissions with chmod
- Changing ownership with chown
- File searching with find
- Grep command
- File compression
- Managing processes
- Package management
- System monitoring

---

# Linux File Permissions

Linux uses a permission system to control access to files and directories.

There are three types of permissions:

- Read (r)
- Write (w)
- Execute (x)

Permissions are applied to three groups:

- Owner
- Group
- Others

Example:
-rwxr-xr--

Meaning:

| Section | Permission |
|-------|-------|
Owner | Read Write Execute |
Group | Read Execute |
Others | Read |

