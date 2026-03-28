# GSL-TW V111: VRPTW Benchmark Performance Data (354 Instances)

## 1. Execution Environment
*   **Processor Architecture:** ARM64 (Mobile-based)
*   **Runtime Environment:** Pydroid 3 (Python Engine)
*   **Constraint Audit:** 100% Verified (Capacity & Time Windows)
*   **Process Type:** Deterministic (Non-Stochastic)

---

## 2. Global Performance Matrix

| Dataset Series | Problem Scale | Success Rate | BKS Match (K) | Avg. Runtime | Operational Status |
| :--- | :--- | :---: | :---: | :---: | :---: |
| **Solomon 100** | 100 Nodes | 100% | 46.4% | 2.78s | Verified |
| **Homberger 200** | 200 Nodes | 100% | 51.7% | 7.57s | Verified |
| **Homberger 400** | 400 Nodes | 100% | 35.0% | 20.00s | Verified |
| **Homberger 600** | 600 Nodes | 100% | 30.0% | 29.20s | Verified |
| **Homberger 800** | 800 Nodes | 100% | 35.0% | 31.15s | Verified |
| **Homberger 1000** | 1,000 Nodes | 100% | 21.6% | 38.22s | Verified |

---

## 3. Statistical Data Breakdown

### 3.1 Solomon 100 Series (56 Files)
*   **BKS (K) Match Count:** 26 / 56
*   **Cumulative Total Distance:** 74,956.09
*   **Total Computation Time:** 155.67s
*   **Operational Status:** Feasibility Verified

### 3.2 Homberger 200 Series (60 Files)
*   **BKS (K) Match Count:** 31 / 60
*   **Cumulative Total Distance:** 239,959.10
*   **Total Computation Time:** 453.91s
*   **Operational Status:** Feasibility Verified

### 3.3 Homberger 400 Series (60 Files)
*   **BKS (K) Match Count:** 21 / 60
*   **Average Solving Speed:** 20.00s per file
*   **Operational Status:** Feasibility Verified

### 3.4 Homberger 600 Series (60 Files)
*   **BKS (K) Match Count:** 18 / 60
*   **Cumulative Total Distance:** 1,190,614.98
*   **Total Computation Time:** 1,751.83s
*   **Operational Status:** Feasibility Verified

### 3.5 Homberger 800 Series (60 Files)
*   **BKS (K) Match Count:** 21 / 60
*   **Cumulative Total Distance:** 1,965,486.68
*   **Total Computation Time:** 1,868.77s
*   **Operational Status:** Feasibility Verified

### 3.6 Homberger 1000 Series (60 Files)
*   **BKS (K) Match Count:** 13 / 60
*   **Cumulative Total Distance:** 3,047,002.87
*   **Total Computation Time:** 2,293.07s
*   **Operational Status:** Feasibility Verified

---

## 4. Auditor Note
All solution paths recorded in the `/Sample_Solutions/` directory have undergone automated validity checks. Each route satisfies all vehicle capacity limits and customer time window requirements with zero tolerance for violations.
