# 🖥️ Operating Systems Project Analyzer

An interactive web application and command-line interface (CLI) built to visualize, analyze, and compare fundamental Operating System algorithms. This project provides step-by-step execution details, theoretical comparisons, and dynamically generated charts for CPU Scheduling, Memory Allocation, and Page Replacement.

---

## ✨ Features

### 1. CPU Scheduling (`cpu_scheduling.py`)
* **Algorithms:** First-Come, First-Served (FCFS) & Priority Scheduling (Non-Preemptive).
* **Metrics Tracked:** Average Waiting Time (WT), Turnaround Time (TAT), and Response Time (RT).
* **Visuals:** Dynamic Gantt Charts and side-by-side bar chart comparisons.

### 2. Memory Allocation (`memory_allocation.py`)
* **Algorithms:** First Fit & Best Fit.
* **Metrics Tracked:** Internal Fragmentation & External Fragmentation.
* **Visuals:** Bar charts depicting memory blocks vs. used space, alongside fragmentation comparisons.

### 3. Page Replacement (`page_replacement.py`)
* **Algorithms:** First-In-First-Out (FIFO) & Least Recently Used (LRU).
* **Metrics Tracked:** Total Page Faults.
* **Visuals:** Line graphs showing cumulative page fault history over time.

---

## 🛠️ Tech Stack

* **Language:** Python 3.x
* **Framework:** [Streamlit](https://streamlit.io/) (for the web UI)
* **Data Processing:** Pandas, NumPy
* **Visualization:** Matplotlib

---

## 📂 Project Structure

```text
├── app.py                  # Main Streamlit web application
├── cpu_scheduling.py       # Logic and visualization for CPU algorithms
├── memory_allocation.py    # Logic and visualization for Memory algorithms
├── page_replacement.py     # Logic and visualization for Page algorithms
├── utils.py                # Helper functions (e.g., input parsing)
└── README.md               # Project documentation
