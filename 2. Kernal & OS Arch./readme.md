# 01 - Kernel and OS Structure

Let’s go deeper into the **core of Linux** — the part that makes the entire system tick: the **Kernel**.

---

## What Is a Kernel?

A **kernel** is the lowest-level part of an operating system. It directly communicates with your hardware, allocates memory, schedules tasks, and controls system resources.

It acts as a bridge between your applications and your machine.

---

## Types of Kernels

| Type           | Description                                          | Example OS         |
|----------------|------------------------------------------------------|--------------------|
| **Monolithic** | Entire OS runs in kernel space (fast, powerful)      | Linux, BSD         |
| **Microkernel**| Minimal code in kernel; more modular, less efficient | Minix, QNX         |
| **Hybrid**     | Mix of both (marketing buzzword in some cases)       | Windows, macOS     |

Linux uses a **monolithic kernel**, but with **loadable modules**, meaning you can insert and remove components (like device drivers) without rebooting.

---

## Kernel Modules

**Modules** = plug-and-play features in the kernel.
Examples:
- Device drivers
- File systems
- Network protocols

## Core Responsibilities of the Linux Kernel
- Process Management:     Scheduling and running tasks
- Memory Management:      Allocating RAM to processes
- Device Drivers:         Handling I/O from hardware
- System Calls:           Providing an API to user programs
- Security & Isolation:   Permissions, namespaces, cgroups

## Linux OS Structure
+---------------------------+
|     Applications (User)   |
+---------------------------+
|         Shell             |
+---------------------------+
|     System Libraries      |
+---------------------------+
|         Kernel            |
+---------------------------+
|        Hardware           |
+---------------------------+





