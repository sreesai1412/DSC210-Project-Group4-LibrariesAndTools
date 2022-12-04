# Performance Analysis of Libraries and Tools on Linear Algebra Operations

#### **Group number:** 4
#### **Group members:**

*   Harshil Jain (A59017538)
*   Sai Sree Harsha (A59020345)
*   Aditya Mandke (A59020008)
*   Omkar Bhope (A59016323)

This repo contains the code for our DSC210 course project. In this project we analyse the performance of 4 different libraries (NumPy, PyTorch, TensorFlow and JAX) on 14 different linear algebra operations. We also compare the performance of these libraries across different hardware (CPU and GPU).
The linear algebra operations across which we compare 

## Requirements
Ensure that the following libraries are installed in your environment. 
```
NumPy
PyTorch
TensorFlow 
JAX
Seaborn
Matplotlib
```
Note that all requirements are readily available by default in the Google Colab environment.


## Performance Analysis on CPU
The `LinearAlgebraBenchmarkCPU.ipynb` notebook contains our experiments to analyse the performance of different libraries on CPU. In each section of the notebook, we consider a particular linear algebra operation. We implement the operation using each of the 4 libraries, record the execution time for different sizes of input matrices and compare performance by plotting the results.

## Performance Analysis on GPU
The `LinearAlgebraBenchmarkGPU.ipynb` notebook contains our experiments to analyse the performance of different libraries on GPU. In each section of the notebook, we consider a particular linear algebra operation. We implement the operation using each of the 4 libraries, record the execution time for different sizes of input matrices and compare performance by plotting the results.

