# Hi there, I'm Mark! 👋

I am a Computer Science student (BCS) at UBC with prior professional engineering experience in system reliability, statistical failure modeling, and quantitative risk analysis. My background is built on bridging complex physical infrastructure with robust, data-driven software solutions. 

As I transition into software development, I am directing my studies and personal projects toward **High-Performance Systems Programming**, **Backend Data Pipelines**, and **Infrastructure/SRE**. I am eager to apply my interest in low-level memory optimization (C++), large-scale data manipulation (Python), and object-oriented design (Java) to build scalable, fault-tolerant software systems in a collaborative environment.

## 🏛️ Industry & Corporate Projects

### [System Risk Model: A Technical Case Study](https://github.com/Mcmecs/System-Risk-Failure-Model)
**Tech Stack:** Python, Pandas, NumPy, SciPy, OpenTURNS | **Domain:** Pipeline Reliability & Operational Risk
* **The Problem:** Quantified the probability of commercial shortfall risk to a pipeline network shipping natural gas to an export market. Because both market demand and system capability are inherently variable, failure is modeled mathematically by calculating the statistical overlap (interference) between their respective probability distributions.
* **Technical Execution:** Developed a **Jupyter Notebook** to model market demand and system capability by fitting optimal continuous Probability Density Functions (PDFs) to historical market data and hydraulically simulated system data using OpenTURNS and SciPy.
* Executed Monte Carlo simulations to evaluate the interference (overlap) of the two distributions, accurately calculating system vulnerability and failure probabilities.
* Supplemented the continuous PDF models with discrete Bernoulli distributions (via NumPy and Pandas) based on recent operational availability data to predict the likelihood of concurrent compressor unit failures and calculate their impact on total system capacity.
* *Note: This repository contains a technical whitepaper demonstrating the technical execution while protecting proprietary corporate IP.*


## 🚀 Personal & Academic Projects

### [Capacity Risk Pipeline & Fleet Optimizer](https://github.com/Mcmecs/capacity-shortfall-model)
**Tech Stack:** Python, SciPy, OpenTURNS, NumPy, Pandas, Pytest, Docker, GitHub Actions (CI), Streamlit, Seaborn, Matplotlib, YAML
* Engineered a fully automated, configuration-driven risk modeling pipeline, building a robust Object-Oriented software architecture from the ground up to replace procedural mathematical models.
* Developed a **Multi-Objective Optimization engine** that evaluates hundreds of server fleet combinations against SLA constraints to generate a Pareto Efficient Frontier, minimizing hardware CapEx/OpEx versus capacity deficit risk.
* Developed a custom **SciPy** statistical fitting module that dynamically ranks and selects optimal data distributions via the Kolmogorov-Smirnov (KS) test.
* Built an interactive **Streamlit** web dashboard that dynamically bridges front-end user inputs with a custom Monte Carlo simulation engine, leveraging **OpenTURNS** copulas to model multivariate dependencies for real-time visualization of capacity deficits and optimal fleet allocations.
* Engineered a seamless data flow using **YAML** configurations to eliminate hardcoded variables, making the analytical pipeline entirely data-driven and easily extensible.
* Containerized the application environment using **Docker** and implemented **GitHub Actions** for continuous integration and automated testing.


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
