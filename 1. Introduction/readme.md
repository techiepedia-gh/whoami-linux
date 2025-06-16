# 00 - Introduction to Linux

Before we dive into commands, scripts, and system internals, let’s get something straight:  
**What even is Linux, and why should you care?**

---

## What is Linux?

**Linux** is an open-source **kernel**, not a full operating system. A **kernel** is the core component of any OS — it manages hardware, memory, processes, and communication between applications and your physical machine.

Most people say "Linux" when they actually mean **GNU/Linux**, which is the kernel + a bunch of tools/utilities (like the shell, package manager, etc.) that make up a complete, usable operating system.

---

## Linux System Structure (Flowchart)

Here’s where the kernel fits in your system:

┌──────────────────────┐
│ User Applications │ ← You interact with this (editors, browsers, terminals)
└────────▲─────────────┘
│
│
▼
┌──────────────────────┐
│ Shell │ ← CLI tools like bash/zsh/Fish etc.
└────────▲─────────────┘
│
▼
┌──────────────────────┐
│ Kernel │ ← Controls CPU, memory, I/O, devices
└────────▲─────────────┘
│
▼
┌──────────────────────┐
│ Hardware │ ← Your actual machine
└──────────────────────┘


> The kernel is the bridge between **software** and **hardware**.

---

## Why Learn Linux?

Here’s why Linux matters:
If you're serious about tech, *Linux is non-negotiable*.

---

## 💻 GUI vs CLI

Linux gives you both:

- **GUI**: Graphical User Interface >>> Easier to use, limited control
- **CLI**: Command Line Interface   >>> More power, more flexibility, especially for servers

This course is CLI-first — because real Linux user lives in the terminal.

---

## Common Linux Distributions (Distros)

Here's a quick comparison:

| Distro        | Based On | Use Case                          |
|---------------|----------|-----------------------------------|
| Ubuntu        | Debian   | General desktop/server            |
| Fedora        | Red Hat  | Workstations, development         |
| Arch Linux    | -        | DIY, bleeding-edge, minimal       |
| Kali Linux    | Debian   | Security & ethical hacking        |
| Alpine Linux  | -        | Containers, lightweight systems   |

> Pick what suits your needs — they all run the same core.
> I user Fedora by the way!!!!

---


## ✅ Section Checklist

Make sure you can:

- [ ] Explain what a kernel is
- [ ] Describe the relationship between kernel, shell, and hardware
- [ ] Differentiate between Linux (kernel) and GNU/Linux (complete OS)
- [ ] Explain why CLI is preferred for serious Linux use
- [ ] Understand the structure of a basic Linux system

---
