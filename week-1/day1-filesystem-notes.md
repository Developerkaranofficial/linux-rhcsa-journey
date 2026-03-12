# Day 1 — Filesystem Navigation
Date: March 2026

## What I Learned Today
The Linux filesystem starts from a single root directory called /
Everything on the system lives inside this one tree structure.

## Key Directories
| Directory | Purpose |
|-----------|---------|
| /etc      | System configuration files |
| /home     | User home directories |
| /var      | Logs and variable data |
| /boot     | Files needed to start the system |
| /tmp      | Temporary files cleared on reboot |
| /usr      | User programs and utilities |

## Commands I Used Today
```bash
cat /etc/os-release   # shows what version of RHEL you are running
whoami                # shows current logged in user
hostname              # shows system hostname
uname -a              # shows kernel and system information
ls /                  # lists top level directories
man hier              # manual explaining filesystem hierarchy
```

## One Thing I Will Remember
The Linux filesystem is one big tree. Everything
hangs from / like branches from a trunk.
```



