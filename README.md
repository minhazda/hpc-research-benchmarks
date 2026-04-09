# HPC & Parallel Compute Benchmarks for ML Workloads

This repository houses performance engineering benchmarks and parallel implementations, demonstrating the application of High-Performance Computing (HPC) techniques to data science and ML workflows. 

## 🎯 Current Implementations
1. **C++ OpenMP Solver:** Parallelised Jacobi iteration demonstrating low-level shared-memory multiprocessing, thread management, and speedup profiling. Achieved a **4.81x speedup** using 8 threads on a university cluster.
2. **Parallel Feature Engineering (Python):** Benchmarking parallel execution (via `joblib`/`multiprocessing`) for generating hundreds of rolling-window and lag features across large SKU datasets.

## 🔬 Research Direction (PhD Pitch)
I am currently extending this work to bridge **Privacy-Preserving Machine Learning (PPML)** and **HPC**. Future commits will include:
* Benchmarking the computational overhead of **Differential Privacy (DP-SGD)** on large-scale synthetic time-series.
* Multi-node scaling for federated forecasting models in industrial/energy settings using MPI and Dask/Ray.
* Scalability testing on national supercomputing infrastructure (e.g., Pawsey/NCI in Australia).

*(This repository demonstrates systems-level competence supporting my primary ML research in privacy-preserving synthetic data generation).*
