# Image Compression using Singular Value Decomposition (SVD)

## Overview

This project explores image compression using **Singular Value Decomposition (SVD)**,
a linear algebra technique used for low-rank matrix approximation.

The goal of the project is to understand how reducing the matrix rank affects
image reconstruction quality and compression performance.

This project was developed as part of an **Abstract Linear Algebra course project**
at Coe College.

---

## Method

An image can be represented as a matrix where each entry corresponds to a pixel value.

Using SVD, the image matrix **A** can be decomposed as:

A = UΣVᵀ

By keeping only the top **k singular values**, we can reconstruct an approximation
of the original image.

Smaller values of **k** result in stronger compression but lower image quality.

---

## Project Files

- **Deliverable.ipynb** – Jupyter Notebook containing the full analysis and experiments
- **luo.jpg** – original image used for compression experiments
- **Memo.pdf** – project summary and discussion
- **Topic.pdf** – project proposal / topic description
- **Reference.pdf** – references used in the project

---

## Key Questions

- How does the rank **k** affect reconstruction quality?
- What is the trade-off between compression ratio and image fidelity?

---

## Tools

Python  
NumPy  
Matplotlib  
Jupyter Notebook  

---

## Author

Shuyun (Esther) Chen  
Mathematics Student, Coe College  
