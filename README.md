# Performance Analysis of Libraries and Tools on Linear Algebra Operations

**Course:** DSC210: Numerical Linear Algebra for Data Science

**Instructor:** Dr. Tsui-wei Weng

**Group number:** 4

**Group topic:** Topic 10: Libraries and Tools

**Group members:**

*   Harshil Jain (A59017538)
*   Sai Sree Harsha (A59020345)
*   Aditya Mandke (A59020008)
*   Omkar Bhope (A59016323)

This repo contains the code for our DSC210 course project. In this project we analyse the performance of 4 different libraries (NumPy, PyTorch, TensorFlow and JAX) on 14 different linear algebra operations. We also compare the performance of these libraries across different hardware (CPU and GPU).
The linear algebra operations which we use to conduct our analysis include,
```
Matrix-matrix multiplication
Matrix-vector multiplication
Vector-vector multiplication
Trace
Transpose
Inverse
Determinant
Adjoint
Cholesky decomposition
LU decomposition
QR factorization
Eigenvalue and Eigenvector computation
PCA
SVD
```

## Instructions
1. Ensure that the following libraries are installed in your environment. 
```
numpy==1.21.6
torch==1.12.1
tensorflow==2.9.2
jax==0.3.25
seaborn==0.11.2
matplotlib==3.2.2
numba==0.56.4
```
Note that all requirements are readily available by default in the Google Colab environment.

2. Open [`LinearAlgebraBenchmarkCPU.ipynb`](https://github.com/sreesai1412/DSC210-Project-Group4-LibrariesAndTools/blob/main/LinearAlgebraBenchmarkCPU.ipynb) and run all the cells.

3. Open [`LinearAlgebraBenchmarkGPU.ipynb`](https://github.com/sreesai1412/DSC210-Project-Group4-LibrariesAndTools/blob/main/LinearAlgebraBenchmarkGPU.ipynb) and run all the cells.

## Performance Analysis on CPU
The [`LinearAlgebraBenchmarkCPU.ipynb`](https://github.com/sreesai1412/DSC210-Project-Group4-LibrariesAndTools/blob/main/LinearAlgebraBenchmarkCPU.ipynb) notebook contains our experiments to analyse the performance of different libraries on CPU. In each section of the notebook, we consider a particular linear algebra operation. We implement the operation using each of the 4 libraries, record the execution time for different sizes of input matrices and compare performance by plotting the results.

The plots generated by the experiments can be found at [`CPU_plots`](https://github.com/sreesai1412/DSC210-Project-Group4-LibrariesAndTools/blob/main/CPU_plots/).

## Performance Analysis on GPU
The [`LinearAlgebraBenchmarkGPU.ipynb`](https://github.com/sreesai1412/DSC210-Project-Group4-LibrariesAndTools/blob/main/LinearAlgebraBenchmarkGPU.ipynb) notebook contains our experiments to analyse the performance of different libraries on GPU. In each section of the notebook, we consider a particular linear algebra operation. We implement the operation using each of the 4 libraries, record the execution time for different sizes of input matrices and compare performance by plotting the results.

The plots generated by the experiments can be found at [`GPU_plots`](https://github.com/sreesai1412/DSC210-Project-Group4-LibrariesAndTools/blob/main/GPU_plots/).

## Report

A detailed report detailing the comparison of the above mentioned operations on CPU and GPU can be found [`here`](https://www.notion.so/FINAL-Topic-10-Performance-Analysis-of-Libraries-and-Tools-on-Linear-Algebra-Operations-caf28f9f2bc24a2aacb92d09f594f684)
