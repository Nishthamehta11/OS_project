# OS_Project

**Author:** Nishtha Mehta
Anureet kaur

This repository contains an implementation of various CPU scheduling algorithms as part of an Operating Systems project.

## Table of Contents
- [Overview](#overview)
- [Algorithms Implemented](#algorithms-implemented)
- [Installation](#installation)
- [Usage](#usage)
- [Input Format](#input-format)
- [Project Structure](#project-structure)
- [Contributors](#contributors)

## Overview
In this project, we simulate and compare the behavior of multiple CPU scheduling algorithms. The simulator can produce a trace timeline or statistical summary for each algorithm, helping to visualize and analyze:
- Average turnaround time
- Normalized turnaround time
- Waiting time patterns

## Algorithms Implemented
1. **First Come First Serve (FCFS)**
2. **Round Robin (RR)**
   - Supports variable time quantum
3. **Shortest Process Next (SPN)**
4. **Shortest Remaining Time (SRT)**
5. **Highest Response Ratio Next (HRRN)**
6. **Feedback (FB-1)**
7. **Feedback with increasing quantum (FB-2i)**
8. **Aging**

## Installation

Ensure you have a C++17‑capable compiler (GCC or Clang) installed.

```bash
# Clone the repo
git clone https://github.com/Nishthamehta11/OS_project.git
cd OS_project

# Build (replace g++-14 with your compiler if needed)
g++-14 main.cpp -std=c++17 -o scheduler
