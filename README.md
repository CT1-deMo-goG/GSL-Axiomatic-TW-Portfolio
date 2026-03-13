[อ่านภาษาไทยคลิกที่นี่](README_TH.md)
# GSL-TW V111: Axiomatic Restoration
### **High-Performance Deterministic VRPTW Solver Portfolio**

GSL-TW V111 is a proprietary computational engine specifically engineered for the **Vehicle Routing Problem with Time Windows (VRPTW)**. Developed on the **Axiomatic Computing Architecture (AXIN)**, the solver focuses on extreme computational efficiency and deterministic reliability.

Unlike standard stochastic metaheuristics, GSL-TW utilizes a structured axiomatic framework to pinpoint near-optimal solutions (BKS) with ultra-low latency, making it a "Production-Ready" solution for large-scale industrial logistics.

---

## **Key Characteristics**
- **Unified Scalability:** A single-script architecture solving all scales from 100 to 1,000 customer nodes.
- **Mobile-Optimized Efficiency:** Developed and verified on a mobile environment (Pydroid 3), demonstrating superior algorithmic leverage over hardware power.
- **Deterministic Reliability:** Zero stochastic variance; every execution on the same dataset yields consistent, auditable results.
- **Real-World Speed:** 1,000-node instances solved within ~38 seconds, a runtime suitable for dynamic and real-time operational planning.

---

## **Benchmark Performance Portfolio**
The engine has been verified against the complete Solomon and Homberger benchmark spectrum. The following data summarizes the performance across all supported problem sizes.

| Dataset Series | Problem Scale | BKS Match Rate | Avg. Runtime (Mobile) |
| :--- | :--- | :--- | :--- |
| **Solomon-100** | Small (100 nodes) | 46.4% | ~2.78 s |
| **Solomon-200** | Mid (200 nodes) | 51.7% | ~7.57 s |
| **Homberger-400** | Large (400 nodes) | 35.0% | ~20.0 s |
| **Homberger-600** | Large (600 nodes) | 30.0% | ~29.20 s |
| **Homberger-800** | Massive (800 nodes) | 35.0% | ~31.15 s |
| **Homberger-1000** | Massive (1,000 nodes) | 21.6% | ~38.22 s |

*Note: All solutions are **Audit Verified** (100% feasibility regarding capacity and time window constraints).*

---

## **Technical Strategy & Architecture**
The V111 "Axiomatic Restoration" replaces exhaustive brute-force search with:
1. **Geometric Sensing:** Pinpointing high-quality initial clusters based on spatial axioms.
2. **Deterministic Vehicle Minimization (K-Focus):** Prioritizing fleet reduction before distance refinement.
3. **Temporal Constraint Synchronization:** Precision handling of tight time windows without exponential complexity growth.

---

## **Portfolio Contents**
- **/Benchmark_Logs/**: Detailed execution logs for all instance sets.
- **/Sample_Solutions/**: Verified .txt routing paths for independent validation.
- **/Performance_Captures/**: Screenshots of real-time execution on mobile environments.

**Disclaimer:** This repository is a performance portfolio. The **Source Code is proprietary** and not disclosed. The technology is available for professional routing services and industrial collaboration.

---

## **Professional Contact**
**Independent Researcher: Chonmapoohm Thamsuwan (CTSuwan)** **Email:** ctsuwan@proton.me  

Available for professional collaboration, high-precision routing optimization, and logistics modeling consultancy.

**Service Platforms:**
- **Upwork:** [https://www.upwork.com/freelancers/~0173b4a58a1a327fd6?mp_source=share]
- **Fastwork:** [https://fastwork.co/user/gsl_axiomatic_engine/ai-consultant-14686934?source=app_seller-center_my-service_share-link]

