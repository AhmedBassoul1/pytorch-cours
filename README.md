# PyTorch Fundamentals

A beginner-friendly notebook that introduces the core concepts of PyTorch tensors and basic tensor operations. Because apparently humanity decided linear algebra alone was not intimidating enough, so now tensors come with GPU acceleration.

## Overview

This project is a hands-on introduction to:

* Installing and importing PyTorch
* Creating tensors
* Understanding tensor dimensions and shapes
* Accessing tensor elements
* Working with scalar, vector, and matrix tensors
* Generating random tensors
* Creating zero-filled tensors

The notebook is designed for beginners who want to start learning deep learning and tensor manipulation with PyTorch.

## Project Structure

```text
.
├── 0-fundamental.ipynb   # Main notebook containing PyTorch fundamentals
└── README.md             # Project documentation
```

## Requirements

Install the required libraries before running the notebook:

```bash
pip install pandas numpy matplotlib
pip install torch torchvision --index-url https://download.pytorch.org/whl/cpu
```

## Getting Started

1. Clone the repository:

```bash
git clone <your-repository-url>
cd <your-project-folder>
```

2. Launch Jupyter Notebook:

```bash
jupyter notebook
```

3. Open:

```text
0-fundamental.ipynb
```

4. Run the notebook cells step by step.

## Topics Covered

### 1. Scalars

Learn how to create single-value tensors:

```python
scalar = torch.tensor(7)
```

### 2. Vectors

Create one-dimensional tensors:

```python
vector = torch.tensor([10, 11])
```

### 3. Matrices

Work with two-dimensional tensors:

```python
matrix = torch.tensor([[8, 10], [9, 11]])
```

### 4. Tensor Properties

Understand:

* `.shape`
* `.ndim`
* `.item()`

### 5. Random Tensors

Generate tensors with random values:

```python
rand_tensor = torch.rand(size=(3, 4))
```

### 6. Zero Tensors

Create tensors filled with zeros:

```python
zeros = torch.zeros(5, 6)
```

## Learning Goals

By the end of this notebook, you should be able to:

* Understand the basics of tensors
* Differentiate between scalars, vectors, and matrices
* Inspect tensor dimensions and shapes
* Create tensors for machine learning workflows
* Build a foundation for deeper PyTorch concepts

## Recommended Next Steps

After finishing this notebook, consider learning:

* Tensor operations
* Tensor broadcasting
* GPU acceleration with CUDA
* Automatic differentiation (`autograd`)
* Neural networks with `torch.nn`
* Training deep learning models

## Resources

* urlPyTorch Official Documentation[https://pytorch.org/docs/stable/index.html](https://pytorch.org/docs/stable/index.html)
* urlPyTorch Tutorials[https://pytorch.org/tutorials/](https://pytorch.org/tutorials/)

## License

This project is open source and available under the MIT License.

---

Built for learning, experimentation, and the ancient human ritual of printing tensor shapes until the errors stop appearing.

