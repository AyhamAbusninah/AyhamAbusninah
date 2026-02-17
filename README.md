<div align="center">

# Systems Engineering — Low-level Infrastructure & Runtime Design

[![OS](https://img.shields.io/badge/OS-Linux-1a1a2e?style=flat-square&logo=linux&logoColor=white)](https://kernel.org)
[![Lang](https://img.shields.io/badge/Lang-C-1a1a2e?style=flat-square&logo=c&logoColor=white)](#)
[![Lang](https://img.shields.io/badge/Lang-C++-1a1a2e?style=flat-square&logo=cplusplus&logoColor=white)](#)
[![Focus](https://img.shields.io/badge/Focus-Systems_Engineering-1a1a2e?style=flat-square&logo=gnubash&logoColor=white)](#)

</div>

> I build systems from scratch to understand how machines actually work.

My focus is **low-level engineering**: operating systems, process models, memory behavior, concurrency, and distributed runtimes.  
I am particularly interested in designing infrastructure capable of supporting **next-generation intelligent systems**.

This space documents my ongoing work in **systems engineering** and **runtime design**.

---

## ⚡ Current Focus

- **Unix Internals** & process lifecycle
- **Memory management** and performance behavior
- **Concurrency**, synchronization, and scheduling
- **Distributed compute runtimes** *(in progress)*
- Systems architecture for **large-scale intelligent computation**

---

## 🧠 Engineering Philosophy

> *I treat each project as an engineering exploration into how real systems behave under constraints.*

- Build from **first principles**
- No heavy frameworks or hidden abstractions
- Understand the **cost of every layer**
- **Control** over convenience
- **Correctness** and clarity over speed

---

## 🛠️ Core Stack

### Languages

| | Language | Status |
|---|---|---|
| ![C](https://img.shields.io/badge/-C-2b2b3d?style=flat-square&logo=c&logoColor=white) | **C** | Primary |
| ![C++](https://img.shields.io/badge/-C++-2b2b3d?style=flat-square&logo=cplusplus&logoColor=white) | **C++** | Active |
| ![Rust](https://img.shields.io/badge/-Rust-2b2b3d?style=flat-square&logo=rust&logoColor=white) | **Rust** | Planned |

### Environment

| | Tool | |
|---|---|---|
| ![Linux](https://img.shields.io/badge/-Linux-2b2b3d?style=flat-square&logo=linux&logoColor=white) | **Linux** | Primary development environment |
| ![POSIX](https://img.shields.io/badge/-POSIX-2b2b3d?style=flat-square&logo=gnubash&logoColor=white) | **POSIX** | Systems programming |
| ![GDB](https://img.shields.io/badge/-GDB-2b2b3d?style=flat-square&logo=gnu&logoColor=white) | **gdb / valgrind / strace** | Low-level debugging |

### Concepts

| Domain | |
|---|---|
| **Process orchestration** | **File descriptor management** |
| **Signals & process control** | **Synchronization primitives** |
| **Binary protocols & IPC** | **Scheduler behavior** |

---

## 🐧 Selected Work

### Unix Command Runtime

> A full Unix command execution runtime written in **C**.

Explores how shells actually execute and coordinate processes.

| Area | Detail |
|:---|:---|
| ✅ | **Parsing** & AST construction |
| ✅ | **Pipelines** and file descriptor orchestration |
| ✅ | **Signal handling** |
| ✅ | **Builtins** and execution engine |
| ✅ | Strict **memory discipline** |

---

### Concurrency Lab *(ongoing)*

> Exploration of **synchronization**, timing, and scheduling behavior in multi-threaded systems.

| Area | Detail |
|:---|:---|
| 🔬 | **Thread coordination** |
| 🔬 | **Starvation** and fairness |
| 🔬 | **Timing precision** |
| 🔬 | **Locking strategies** |

---

### Distributed Runtime *(in progress)*

> Minimal distributed compute runtime designed to execute workloads across multiple Linux nodes using **raw system primitives**.

| Area | Detail |
|:---|:---|
| 🔧 | **Worker lifecycle** & supervision |
| 🔧 | **Binary TCP** communication |
| 🔧 | **Scheduling** & failure recovery |
| 🔧 | Transparent **system behavior** |

---

## 🧭 Direction

My long-term direction is **systems infrastructure** for high-performance and intelligent computation:

- **Distributed runtimes**
- **Execution engines**
- **Compute orchestration**
- System-level architecture for **future intelligent machines**

---

## 📬 Contact

> Open to discussions with engineers working on:
> **systems infrastructure**, **distributed runtimes**, and **low-level architecture**.
