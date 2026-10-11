# Embedded Linux Notes — كورس Embedded Linux بالمصري

[![Live Site](https://img.shields.io/badge/Live%20Site-GitHub%20Pages-2ea44f?logo=github)](https://mkko000.github.io/embedded-linux-notes/)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
![Language](https://img.shields.io/badge/Language-Egyptian%20Arabic-orange)
![Modules](https://img.shields.io/badge/Modules-29-purple)

An original, deep **Embedded Linux** course in Egyptian Arabic by **Mohammed El Sisi** — 29 modules (plus two "think, don't memorize" sections) in one self-contained page: how things work under the hood, why they were designed that way, and how they compare to bare-metal microcontrollers.

## 🌐 Live site
**https://mkko000.github.io/embedded-linux-notes/**

## 📚 Modules

| Module | Topic |
|---|---|
| 1 | OS, the Kernel & why Embedded Linux (+ toolchain, U-Boot, device tree, Buildroot, Yocto) |
| 2 | The Shell, users, paths & first commands |
| 3 | `cp`, `mv`, `rm`, `cal`, `date`, `wc` |
| 4 | Wildcards (globbing) |
| 5 | Help, `cat`/`echo`/`sort`/`uniq`, `&&` / `\|\|`, redirection |
| 6 | `head`/`tail`, `less`/`more`, `grep`, pipes & quoting |
| 7 | Regular expressions |
| 8 | Text editors: `nano`, `vim`, `gedit` |
| 9 | User & group management |
| 10 | Ownership & permissions |
| 11 | Searching: `find` & `locate` |
| 🧠 | Think, don't memorize: anatomy of a command, option conventions, `--help`/`man` discovery ladder |
| ✍️ | Vim/Neovim from the inside: the operator×motion grammar, TTY/PTY & terminfo, buffer vs file, `$EDITOR`/`sudoedit` |
| 12 | Shell scripting basics: shebang, variables, quoting, `read`, arguments |
| 13 | Environment & init files: `export`, `.bashrc`/`.profile`, aliases, history |
| 14 | `cut`, `paste`, `sort`, `tr`, `diff`, `patch` |
| 15 | `sed` & `awk` |
| 16 | Compression & archives: `gzip`/`bzip2`/`xz`, `tar` |
| 17 | Filesystems & partitions: inodes, links, MBR/GPT, `mkfs`, `mount`, `fstab` |
| 18 | Packages: `dpkg`, `apt`, `.deb` internals |
| 19 | Processes: `ps`, `top`, jobs, `nice` |
| 20 | Signals & `kill`, process states, zombies |
| 21 | `at`, `cron`, daemons |
| 22 | Logs: rsyslog, `logrotate`, `journalctl` |
| 23 | The boot process in detail: BIOS/UEFI, GRUB, initramfs, systemd |
| 24 | Networking fundamentals: MAC/IP, subnetting, DHCP, DNS, NAT |
| 25 | `ip`, `ping`, TTL, `ssh`, keys, `scp` |
| 26 | Bash conditions: `[ ]`, `[[ ]]`, `(( ))`, file tests, `case` |
| 27 | Arithmetic & loops |
| 28 | Arrays, string operations, `select` |
| 29 | Functions, exit codes, `trap`, debugging |

## ✨ Features
- **Built-in Linux terminal simulator** (🖥️ button, or <kbd>Ctrl</kbd>+<kbd>`</kbd>) — a fake Debian 13 machine running fully in the browser: filesystem, users & groups, permissions, `sudo`/`su`, pipes, redirection (`2>&1`, `/dev/null`), globbing & brace expansion, `$(...)`, history, Tab completion. 210+ commands (now incl. `sed`, `awk`, `paste`, `diff -u`/`patch`, `tar`/`gzip`/`xz`, `ps`/`kill`/jobs, `at`, `logger`/`journalctl`, `apt`/`dpkg`, `test`/`[`, `$(( ))`, `bc`, `mount`, `ssh-keygen`) with GNU-style outputs and error messages (`ls`, `find`, `grep`, `sort`, `cut`, `chmod`, `useradd`, `usermod`, `passwd`, `chage`, `gcc`, …). State is saved locally; one-click reset.
- **▶ Try-it buttons** on every recorded terminal session — sends the commands straight into the simulator.
- **32 guided missions** (about 3 per module) that check themselves as you type, with hints and step-by-step solutions.
- **Gamification** — XP, 11 levels, 16 badges, daily streak, per-module progress, confetti, and a progress dashboard.
- **Per-module quizzes** — multiple choice, *type the command* (validated by running it in a sandbox), drag-to-order and matching, each with an explanation.
- **Flashcards with spaced repetition** (Leitner boxes) built from the cheat-sheet and the glossary.
- **Vim trainer** — a real modal editor with 12 exercises (motions, operators, undo, `:%s`, `:wq`).
- **Playgrounds** — clickable permission bits (SUID/SGID/sticky) and a `umask` board, regex tester with a live pattern explainer, an animated boot sequence, and an animated RM/EDF scheduler.
- **👑 Boss Challenge** — a timed 15-minute exam from all 11 modules with a per-module score report.
- **64 real terminal sessions** — actually executed on Debian 13, with every output line explained.
- **"Common mistake" tips**, searchable cheat-sheet and glossary.
- Readable typography, light/dark theme, RTL Arabic with isolated English commands, mobile friendly, works offline (single self-contained HTML file, no network requests).

## 🇪🇬 بالعربي
كورس Embedded Linux كامل بالمصري في 29 وحدة (Module) — صفحة واحدة. الشرح بيدخل في العمق: إزاي كل حاجة شغالة من جوه وليه، مع مقارنة بالـ microcontroller، و64 جلسة terminal حقيقية مشروحة سطر سطر، و<b>terminal Linux محاكي</b> جوه الصفحة، و32 mission بتتصحح أوتوماتيك، و XP و levels و badges، و quizzes، و flashcards، و vim trainer، و Boss Challenge بالوقت، و cheat-sheet، ونصايح «خلي بالك — غلطة شائعة».
افتح الموقع: https://mkko000.github.io/embedded-linux-notes/

## 👤 Author
**Mohammed El Sisi** — [@Mkko000](https://github.com/Mkko000)

## 📄 License
Released under the [MIT License](LICENSE).
