# linux-notes

My personal notes, references, and documentation for learning Linux — organized by topic for future reference.

## Topics

1. [01 — Linux Introduction](./01-linux-introduction) — what Linux is, history, distributions, open source
2. [02 — File System & Navigation](./02-file-system-and-navigation) — directory structure, paths, `cd`, `ls`, `pwd`, `tree`
3. [03 — Commands & Utilities](./03-commands-and-utilities) — core GNU/coreutils commands, text tools, pipes, redirection
4. [04 — Users, Groups & Permissions](./04-users-groups-permissions) — ownership, `chmod`, `chown`, `sudo`, ACLs
5. [05 — Processes & Services](./05-processes-and-services) — `ps`, `top`, `kill`, systemd, journals
6. [06 — Package Management](./06-package-management) — apt, dnf/yum, pacman, flatpak, snap
7. [07 — Shell Scripting](./07-shell-scripting) — bash syntax, variables, loops, functions, one-liners
8. [08 — Networking](./08-networking) — IP, routing, SSH, firewalls, diagnostics
9. [09 — Storage & Filesystems](./09-storage-and-filesystems) — mounts, partitions, LVM, RAID, quotas
10. [10 — System Administration](./10-system-administration) — boot, logs, cron, performance, kernel
11. [11 — Security](./11-security) — hardening, SELinux/AppArmor, audit, PAM
12. [12 — Troubleshooting](./12-troubleshooting) — common issues, recovery, debugging tools

## Conventions

- Each topic lives in its own numbered folder.
- Notes are written in Markdown.
- Diagrams and screenshots go in [`assets/`](./assets).
- File names use `kebab-case.md`.
- Commands are shown in code blocks with the relevant shell tag, e.g. `bash`.

## How I take notes

- One `.md` file per sub-topic inside a topic folder.
- Each note starts with a short summary, then commands/examples, then references.
- Keep it practical — favor examples and gotchas over theory.