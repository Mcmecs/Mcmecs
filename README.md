# Hi there, I'm Mark! 👋

I am a Computer Science student at UBC with prior professional engineering experience in system reliability, statistical failure modeling, and quantitative risk analysis. My background is built on bridging complex physical infrastructure with robust, data-driven software solutions. 

As I transition into software development, I am directing my studies and personal projects toward **High-Performance Systems Programming**, **Backend Data Pipelines**, and **Infrastructure/SRE**. I am eager to apply my interest in low-level memory optimization (C++), large-scale data manipulation (Python), and object-oriented design (Java) to build scalable, fault-tolerant software systems in a collaborative co-op environment.

## 🏛️ Industry & Corporate Projects

### [System Probabilistic Risk & Concurrent Failure Model (Corporate Case Study & Clone)](https://github.com/Mcmecs/System-Risk-Failure-Model)
**Tech Stack:** Python, Pandas, NumPy, SciPy, OpenTURNS | **Domain:** Pipeline Reliability & Operational Risk
* **The Problem:** How do we realistically quantify the shortfall risk of a major pipeline network to justify increased contract flow levels? Because conventional static, "worst-case scenario" methods artificially limit capacity, this project was engineered to unlock the system's true potential by dynamically modeling the interplay of varying market demand, base system capability, and concurrent equipment failures.
* **Technical Execution:** Engineered a **Probabilistic Risk Assessment (PRA)** engine utilizing Monte Carlo simulations to project seasonal and annual shortfall days for executive decision-makers.
* Architected a **Demand-Capacity Interference Model** to calculate system vulnerability. By fitting optimal continuous Probability Density Functions (PDFs) to historical market demand and base capacity using OpenTURNS and SciPy, the model evaluates the mathematical intersection (overlap) of the two distributions to accurately quantify failure probabilities.
* Supplemented the continuous PDF models with discrete Bernoulli distributions (via NumPy/Pandas) based on recent operational availability data to predict concurrent compressor unit outage rates.
* Implemented combinatorial algorithms utilizing Python's `itertools` library to calculate independent failure probabilities across multi-unit systems, algorithmically filtering over 33 million mutually exclusive outage events to eliminate computational memory bottlenecks.
* *Note: This repository contains a technical whitepaper and a sanitized codebase using dummy data to demonstrate the system architecture while protecting proprietary corporate IP.*

## 🚀 Personal & Academic Projects

### [High-Performance C++ Matrix & Math Library](https://github.com/Mcmecs/Tensor_lib)
**Tech Stack:** C++, SIMD, Pybind11, CMake, GoogleTest, Valgrind, GitHub Actions (CI)
* Engineered a custom high-performance 2D array (matrix) library from scratch, utilizing **Pybind11** to expose the C++ backend as a fully functional Python module.
* Conducted rigorous performance profiling and benchmarking, achieving a **50x increase in computational speed** over standard implementations by replacing nested vectors with a single contiguous 1D array (`row * width + col`) to maximize L1 cache spatial locality.
* Further optimized throughput by implementing **SIMD vectorization** for parallel data processing at the hardware register level.
* Enforced strict, leak-free memory management utilizing **Valgrind** and modern C++ **Move Semantics (Rule of Five)** to eliminate expensive deep copies during temporary object allocation.
* Implemented comprehensive unit testing with **GoogleTest** to verify mathematical accuracy throughout development, integrated into an automated **GitHub Actions** and **CMake** CI pipeline to run regressions on every push.

### [Java Run Log Application](https://github.com/Mcmecs/Java-Run-Log-Application)
**Tech Stack:** Java, Java Swing, JUnit
* Developed a desktop GUI application using object-oriented design principles to log, manage, and visualize user running data.
* Implemented equivalence class partitioning and designed rigorous JUnit test cases to ensure broad test coverage and application stability.

---
📫 **Let's Connect:** [www.linkedin.com/in/mark-y-cheung] [mark.hwarang82@gmail.com]
