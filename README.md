# Linux Device Driver Learning on i.MX6ULL

[![License](https://img.shields.io/badge/license-Educational-blue)](LICENSE)

This repository contains Linux kernel driver examples and supporting user-space applications developed on the **i.MX6ULL** development board. The project is intended for learning and practicing Linux device driver development on embedded platforms.


---

## Overview

The purpose of this repository is to provide practical examples of Linux device driver development on the i.MX6ULL platform. Key areas covered include:

- Character device driver implementation for controlling GPIO-based LEDs.
- Memory-mapped I/O access using `ioremap` and `readl`/`writel`.
- Device Tree (DT) integration for hardware description and driver binding.
- Safe data transfer between user space and kernel space using `copy_from_user` and `copy_to_user`.
- Kernel module management, `cdev` initialization, and device file creation.

---

## Learning Goals

By exploring the examples in this repository, you will learn:

1. How to write Linux kernel modules for embedded devices.
2. How to use Device Tree to describe hardware resources.
3. How to map physical registers into kernel virtual memory safely.
4. How to interface kernel drivers with user-space applications.
5. How to implement basic GPIO control using Linux drivers.

