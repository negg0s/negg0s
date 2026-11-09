<div align="center">

# NEGG0

**Systems Programmer • Low-Latency Audio & DSP • Windows & Linux Internals**

[![C++20](https://img.shields.io/badge/C++20-00599C?style=flat-square&logo=c%2B%2B&logoColor=white)](https://isocpp.org/)
[![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=white)](https://en.wikipedia.org/wiki/C_(programming_language))
[![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)](https://python.org/)
[![Linux Kernel](https://img.shields.io/badge/Linux_Kernel-FCC624?style=flat-square&logo=linux&logoColor=black)](https://kernel.org/)
[![Win32 NTAPI](https://img.shields.io/badge/Win32_NTAPI-0078D6?style=flat-square&logo=windows&logoColor=white)](https://learn.microsoft.com/windows/)
[![CMake](https://img.shields.io/badge/CMake-064F8C?style=flat-square&logo=cmake&logoColor=white)](https://cmake.org/)

<p align="center">
  <i>"I build whatever I find interesting: tools, audio engines, compilers, forensics, low-latency daemons.<br/>I prefer boring interfaces, zero runtime overhead, explicit rollback, and measurements over claims."</i>
</p>

---

</div>

## 📌 Featured Projects (Flagships)

### 🛡️ Windows Internals & Forensics

| Project | Description | Tech Stack |
| :--- | :--- | :--- |
| **[`vmemscan`](https://github.com/negg0s/vmemscan)** | Windows virtual memory and process injection forensics CLI. Audits unbacked executable memory, PEB spoofing, inline hooks, telemetry tampering (ETW/AMSI), direct/indirect syscalls, and sleeping beacon evasion. | `C++20` `Win32 NTAPI` `/MT` |
| **[`obliterator`](https://github.com/negg0s/obliterator)** | Native high-throughput Windows uninstaller and residual cleaner. POSIX unlink batching, handle unlocking via Restart Manager, persistence disarming, and orphaned registry/driver cleanup. | `C++20` `Win32` `Zero-Deps` |
| **[`mftscan`](https://github.com/negg0s/mftscan)** | Fast NTFS Master File Table (MFT) parser and disk volume analyzer CLI for Windows. | `C++20` `NTFS` `Win32` |
| **[`who-locked`](https://github.com/negg0s/who-locked)** | Fast Windows file lock inspector, handle release, and process cleanup utility. | `Python` `Restart Manager` |
| **[`pe-inspector`](https://github.com/negg0s/pe-inspector)** | Static PE (EXE/DLL) binary analyzer, section inspector, and indicator scanner for Windows. | `Python` `Static Analysis` |

### ⚡ Linux Kernel & Low-Latency Systems

| Project | Description | Tech Stack |
| :--- | :--- | :--- |
| **[`zenith-gaming-daemon`](https://github.com/negg0s/zenith-gaming-daemon)** | Ultra-low latency Linux gaming optimization daemon. Netlink process detection, cgroups v2 housekeeping isolation, AMD 3D V-Cache / P-core affinity, PipeWire quantum tuning, sched_ext (`scx`) handoff, and rollback journaling. | `C++20` `Netlink` `cgroups v2` `sched_ext` |
| **[`win-process-tuner`](https://github.com/negg0s/win-process-tuner)** | Lightweight Windows CLI for reversible game and process scheduling tuning, priority, and CPU core affinity. | `Python` `Win32 API` |
| **[`input-latency-bench`](https://github.com/negg0s/input-latency-bench)** | Windows CLI for measuring QueryPerformanceCounter (QPC) overhead and software-observed keyboard timing latency. | `Python` `QPC` `Win32` |

### 🔊 Audio Engineering & DSP

| Project | Description | Tech Stack |
| :--- | :--- | :--- |
| **[`aether-dsp`](https://github.com/negg0s/aether-dsp)** | Non-Euclidean Hyperbolic Waveguide & Modal Cymatics synthesis engine. | `C` `C++20` `SIMD` `DSP` |
| **[`eax-native`](https://github.com/negg0s/eax-native)** | Native Environmental Audio Extensions (EAX) spatial audio for Linux gaming via OpenAL Soft. | `C++` `OpenAL Soft` `PipeWire` |
| **[`pipewire-latency`](https://github.com/negg0s/pipewire-latency)** | Inspect and tune PipeWire buffer latency, quantum sizes, and sample rates on Linux. | `Python` `PipeWire` `Linux` |
| **[`wasapi-latency`](https://github.com/negg0s/wasapi-latency)** | CLI for inspecting and tuning Windows WASAPI audio buffer latency and endpoint periods. | `Python` `WASAPI` `COM` |

### 🧬 Compilers & Machine Learning

| Project | Description | Tech Stack |
| :--- | :--- | :--- |
| **[`VeloC`](https://github.com/negg0s/VeloC)** | Experimental C++ dialect and source-to-source compiler with custom grammar and AST lowering. | `Python` `Clang` `AST` `DSL` |
| **[`chess-ai`](https://github.com/negg0s/chess-ai)** | Chess AI bot and evaluation training pipeline with Stockfish integration. | `Python` `PyTorch` `Stockfish` |
| **[`chess-training-gym`](https://github.com/negg0s/chess-training-gym)** | Data preparation and evaluation toolkit for chess neural network models (FEN encoding, game splitting). | `Python` `Machine Learning` |

---

## 🛠️ Tech Stack & Tooling

| Domain | Technologies & Tools |
| :--- | :--- |
| **Languages** | `C` • `C++20` • `C#` • `Python` • `TypeScript` • `Bash` • `SQL` • `x86-64 ASM` |
| **Operating Systems** | **Linux** (cgroups v2, Netlink, sched_ext, systemd) • **Windows** (NT Native API, Win32) |
| **Audio & DSP** | PipeWire • OpenAL Soft • WASAPI • SIMD Waveguide Synthesis |
| **Build & Tooling** | CMake • Clang / GCC • MSVC • Git • Docker • GDB • ASan / UBSan • libFuzzer |

---

<div align="center">

### 📫 Contact & Notes

Most projects are research, forensic exploration, or hobby systems work.
<br/>
Issues, reproductions, and benchmarks are always more useful than stars.

**Email:** [rokmit599@gmail.com](mailto:rokmit599@gmail.com) • **GitHub:** [@negg0s](https://github.com/negg0s)

</div>
