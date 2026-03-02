# Efficiency Analysis of Pi Estimation via Monte Carlo Method
# (基于蒙特卡罗方法的圆周率估算及其算法效率探究)

## 🚀 Project Overview
This project explores the **Monte Carlo Method** to estimate the value of π (Pi) and focuses on comparing the performance between traditional **Python For-loops** and **NumPy Vectorization**. 

The study demonstrates how high-performance computing techniques (SIMD) can drastically reduce execution time while maintaining high precision.

## 📊 Key Research Findings
* [cite_start]**Vectorization Breakthrough:** Successfully reduced the execution time for 1 million samples from several seconds to only **0.04 seconds**. [cite: 121]
* [cite_start]**Scalability:** The vectorized algorithm handled **5 million samples** in approximately **0.17 seconds**, while the traditional loop method failed (crashed/froze). [cite: 121, 122]
* [cite_start]**Convergence Analysis:** Verified that the estimation error decreases as the sample size increases, following the theoretical $1/\sqrt{N}$ law. 

## 🛠️ Tech Stack
- [cite_start]**Language:** Python 3.12 [cite: 67]
- [cite_start]**Environment:** Visual Studio Code [cite: 67]
- [cite_start]**Libraries:** - `NumPy`: For high-speed vectorized calculations. 
  - [cite_start]`Matplotlib`: For data visualization and efficiency comparison charts. 

## 📈 Performance Comparison
The project automatically generates dual-axis charts to visualize:
1. [cite_start]**Algorithm Efficiency:** Comparison of execution time (Lower is better). [cite: 145]
2. [cite_start]**Precision Convergence:** The trend of error reduction relative to sample size. [cite: 146]


## 📝 Research Log (Highlights)
- [cite_start]**March 2025:** Project initiated; first version developed using basic for-loops. 
- [cite_start]**August 2025:** Major breakthrough by introducing **NumPy Vectorization**. 
- [cite_start]**November 2025:** Completed automated data analysis scripts and addressed Chinese character rendering issues in Matplotlib. 
- [cite_start]**December 2025:** Finalized research report for the **Nantong Youth Science and Technology Innovation Contest**. 

## 🧑‍💻 Author
**Student at Nantong High School (Middle School Section)**
*Passionate about Python, Data Science, and Algorithm Optimization.*# Monte-Carlo-Method
