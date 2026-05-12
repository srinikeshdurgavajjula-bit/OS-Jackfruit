# Multi-Container Runtime

## Project Overview

This project implements a lightweight Linux container runtime in C with support for multi-container execution, process isolation, logging, and kernel-level memory monitoring.

The project uses Linux namespaces, chroot-based filesystem isolation, and a kernel module for monitoring container memory usage.

---

## Features

- Multi-container runtime
- Process isolation using namespaces
- Filesystem isolation using chroot
- Container lifecycle management
- Logging system
- Kernel-space memory monitor
- CPU, memory, and I/O workload testing
- Scheduling analysis

---

## Technologies Used

- C Programming
- Linux Kernel Modules
- Linux Namespaces
- ioctl Communication
- Ubuntu 24.04
- Alpine Linux RootFS

---

## Environment Setup

### VM Configuration

- Ubuntu 24.04
- VirtualBox VM
- Secure Boot Disabled

### Dependency Installation

```bash
sudo apt update
sudo apt install -y build-essential linux-headers-$(uname -r)
