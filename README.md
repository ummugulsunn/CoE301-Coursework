# Computer Architecture (CoE 301)

This repository contains the comprehensive coursework and engineering analysis for the **CoE 301: Computer Architecture** course. The projects demonstrate a deep technical understanding of memory hierarchy performance, cache simulation, and modern I/O subsystem architectures.

## 📖 Course Overview

**Computer Architecture** focuses on the quantitative analysis and design of computing systems. This collection emphasizes:
*   **Memory Systems**: Cache organization, placement policies, and performance tuning.
*   **I/O Subsystems**: Evolution from DMA to modern PCIe and Direct Cache Access (DCA).
*   **System Performance**: Quantitative evaluation using hit rates, latency analysis, and throughput metrics.

## 📂 Repository Contents

### 🚀 [Final Project: Cache Memory Simulation & Analysis](CoE301-Final-Project.pdf)
*   **Format**: Comprehensive Engineering Report (40+ Pages)
*   **Scope**: Design and simulation of a flexible cache memory system to identify optimal configurations for specific instruction traces.
*   **Key Technical Contributions**:
    *   **Simulation Parameters**: Extensive sweep of 81 unique configurations testing **Cache Size** (64B - 256B), **Block Size** (2B - 8B), and **Associativity** (Direct Map to 4-way Set Associative).
    *   **Replacement Policies**: Comparative analysis of **LRU** (Least Recently Used), **FIFO** (First-In, First-Out), and **Random** replacement algorithms.
    *   **Performance Metrics**: Detailed breakdown of Hit Rates vs. Miss Rates for different trace files.
    *   **Outcome**: Empirical data demonstrating the impact of spatial and temporal locality on cache performance.

### 📝 [Assignment 2: High-Performance I/O Architecture](CoE301-Assignment-2.pdf)
*   **Format**: Technical Research & Analysis Report
*   **Scope**: In-depth analysis of the evolution of Input/Output mechanics in modern high-speed computing.
*   **Key Topics Analyzed**:
    *   **DMA vs. Interrupt-Driven I/O**: Quantitative comparison of CPU overhead and context switching costs.
    *   **PCI Express (PCIe)**: Evaluation of switch-based point-to-point topologies and scalable bandwidth (GT/s).
    *   **Direct Cache Access (DCA)**: Investigation into modern Intel DDIO technology, Cache Injection, and eliminating memory bottlenecks in 100Gbps networks.
    *   **Interconnects**: Role of the Ring Interconnect System in low-latency core-to-IO communication.

## 🛠️ Skills & Tools

*   **Simulation & Testing**: Cache performance simulation, parameter sweeping.
*   **Architecture Analysis**: Quantitative reasoning, bottleneck identification (Memory Wall, I/O Overhead).
*   **Technical Writing**: Producing professional engineering documentation with IEEE-style rigor.

## 👤 Author

**Ummugulsun Turkmen**   
*Computer Engineering Student*

---
*Note: This repository serves as an academic portfolio showcasing skills in computer architecture, memory system design, and hardware performance analysis.*
