# Distributed Training & HPC Integration

External libraries and toolkits that enable scaling AI and ML workloads across multiple GPUs, nodes, or HPC clusters, as well as distributed analytics engines commonly used in AI and data-intensive scientific workflows.

---

## Tools

---

### Apache Spark
Apache Spark is a unified distributed analytics engine for large-scale data processing, streaming, machine learning, and graph computation.

- **URL:** https://spark.apache.org/docs/latest/
- **License:** Apache 2.0
- **Operating system:** Unix/MacOS
- **Programming language(s):** Python, R, Java, Scala

---

### Dask
Dask is a flexible Python parallel computing library that scales data science and numerical workloads from a laptop to a cluster.  
It supports distributed array, dataframe, and machine-learning computations.

- **URL:** https://docs.dask.org/en/stable/
- **License:** BSD-3-Clause
- **Operating system:** Unix
- **Programming language(s):** Python

---

### startR
startR is an R package developed at BSC used for high-performance manipulation of multidimensional geoscientific datasets.  
It supports parallel execution and can integrate with HPC systems for large-scale data processing.

- **URL:** https://cran.r-project.org/web/packages/startR/index.html
- **Operating system:** Unix
- **Programming language(s):** R

---

### Triton
Triton is a Python-first language and compiler that allows developers to write custom GPU kernels with performance comparable to CUDA, but with far less boilerplate.

- **URL:** https://github.com/triton-lang/triton
- **License:** MIT
- **Operating system:** Unix
- **Programming language(s):** MLIR, C++, Python

---

### XGBoost
XGBoost is a high-performance distributed gradient boosting library widely used for classical ML tasks and numerical modeling.  
It includes efficient CPU and GPU back-ends and supports distributed execution.

- **URL:** https://xgboost.readthedocs.io/en/stable/
- **License:** Apache 2.0
- **Operating system:** Cross-platform
- **Programming language(s):** Python

---

### Zarr
Zarr is a chunked, compressed, N-dimensional array storage library designed for distributed and cloud-native environments, enabling efficient parallel reads/writes.

- **URL:** https://github.com/zarr-developers/zarr-python
- **License:** MIT
- **Operating system:** Unix
- **Programming language(s):** Python

---

### PyTorch XLA
PyTorch XLA connects PyTorch to the XLA compiler to enable efficient training on Cloud TPUs and other XLA-supported accelerators.

- **URL:** https://github.com/pytorch/xla
- **License:** Apache 2.0
- **Operating system:** Unix
- **Programming language(s):** Python, C++

---

### Ray
Ray is a distributed execution framework for scaling Python and machine learning workloads, including hyperparameter tuning and model serving, across clusters.

- **URL:** https://github.com/ray-project/ray
- **License:** Apache 2.0
- **Operating system:** Unix
- **Programming language(s):** Python, C++

---

### vLLM
vLLM is a high-performance library for large language model inference and serving, optimized for GPU efficiency and throughput.

- **URL:** https://github.com/vllm-project/vllm
- **License:** Apache 2.0
- **Operating system:** Unix
- **Programming language(s):** Python, C++

---

### LMCache
LMCache is a KV-cache management library that enables reusing attention caches across requests to reduce latency and GPU utilization in LLM serving.

- **URL:** https://github.com/LMCache/LMCache
- **License:** Apache 2.0
- **Operating system:** Unix
- **Programming language(s):** Python

---

### Accelerate
Accelerate provides utilities to easily scale PyTorch training across multiple GPUs, TPUs, and mixed precision setups with minimal code changes.

- **URL:** https://github.com/huggingface/accelerate
- **License:** Apache 2.0
- **Operating system:** Unix
- **Programming language(s):** Python

---

### TensorRT
TensorRT is NVIDIA’s high-performance deep learning inference platform, including compilers and runtimes for optimizing and deploying models on NVIDIA GPUs.

- **URL:** https://github.com/NVIDIA/TensorRT
- **License:** Apache 2.0
- **Operating system:** Unix
- **Programming language(s):** C++

---

### NVIDIA Nsight Systems
NVIDIA Nsight Systems is a system-wide performance profiling tool to analyze and optimize CPU and GPU utilization for large-scale applications.

- **URL:** https://developer.nvidia.com/nsight-systems
- **License:** NVIDIA License
- **Operating system:** Unix
- **Programming language(s):** Not applicable

---

### FAISS
FAISS is a library for efficient similarity search and clustering of dense vectors, supporting CPU and GPU back-ends and large-scale indexing.

- **URL:** https://github.com/facebookresearch/faiss
- **License:** MIT
- **Operating system:** Unix
- **Programming language(s):** Python, C++

---

### Apptainer (Singularity)
Apptainer, formerly Singularity, is a container technology designed for secure, portable execution of applications on HPC systems and clusters.

- **URL:** https://github.com/apptainer/apptainer
- **License:** BSD-3-Clause
- **Operating system:** Unix
- **Programming language(s):** Go