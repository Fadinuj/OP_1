# 🐧 Linux System Programming & OS Labs

A comprehensive collection of **System Programming** assignments implemented in **C/C++** under a Linux environment. This repository demonstrates deep understanding of OS concepts, Inter-Process Communication (IPC), toolchain mastery, and performance analysis.

## 📂 Project Overview

### 🛠️ 1. Debugging & Memory Analysis
Demonstration of core system crashes and debugging techniques using `gdb` and `ddd`:
* **Scenarios:** Stack Overflow, Division by Zero, and Invalid Memory Access (Segfault).
* **Analysis:** Core dump analysis and register inspection.

### 📚 2. Dynamic Libraries (Shared Objects)
* **Mandelbrot Set:** Implementation of mathematical set calculations.
* **Shared Library:** Creation of `libmandelbrot.so` and dynamic linking.
* **Usage:** Modular design allowing separate compilation of logic and application.

### 📊 3. Code Coverage & Profiling
* **Dijkstra's Algorithm:** Modified implementation with robust input validation.
* **Coverage (gcov):** Verified 100% code coverage to ensure reliability.
* **Profiling (gprof):** Performance analysis of "Max Sub-Array Sum" algorithms ($O(n^3)$ vs $O(n^2)$ vs $O(n)$) to identify bottlenecks.

### 📡 4. Signals (IPC)
* **Bitwise Communication:** A sender-receiver system that transmits data **bit-by-bit** using only Unix signals (`SIGUSR1`, `SIGUSR2`).
* **Synchronization:** Handling signal timing to prevent data loss without using queues or sockets.

### 📞 5. Pipes & Process Management (Phonebook)
* **Shell Simulation:** A C program that acts like a shell script by orchestrating standard Linux utilities (`grep`, `sed`, `awk`).
* **System Calls:** Extensive use of `fork()`, `exec()`, and `pipe()` to redirect streams and filter data dynamically.

## 🛠️ Tech Stack
* **Languages:** C, C++
* **OS:** Linux (Ubuntu/Debian)
* **Tools:** GCC, Make, GDB, Valgrind
* **Analysis:** gcov (Coverage), gprof (Profiling)

## 💻 How to Run

### Prerequisites
* GCC Compiler
* Make utility
* Linux Environment

### Build & Run
Each module contains its own `makefile`.
1. **Clone the repository:**
   ```bash
   git clone [https://github.com/Fadinuj/Linux-System-Programming-Labs.git](https://github.com/Fadinuj/Linux-System-Programming-Labs.git)
