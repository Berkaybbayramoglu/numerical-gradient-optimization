# Numpy Optimization Lab

A collection of optimization algorithms implemented purely with NumPy. This repository includes a variety of gradient-based optimization methods designed to demonstrate key optimization techniques from scratch, using only basic linear algebra operations. From classic Stochastic Gradient Descent (SGD) to advanced methods like Nesterov Accelerated Gradient (NAG), these algorithms are aimed at anyone looking to understand and implement optimization algorithms in a hands-on, low-level manner.

## Overview

In this repository, you'll find a selection of optimization algorithms implemented purely using NumPy. These methods are designed to minimize loss functions, often used in machine learning tasks. By implementing these algorithms from the ground up, we aim to highlight their underlying mathematical principles while using only NumPy to perform the necessary matrix and vector operations.

### Key Features:
- **Stochastic Gradient Descent (SGD)**
- **Nesterov Accelerated Gradient (NAG)**
- **Function Minimization** using various loss surfaces (e.g., Ellipsoid, Valley, Himmelblau)
- **Interactive visualizations** to track optimization paths
- **No external machine learning libraries** (e.g., TensorFlow, PyTorch) - pure NumPy implementation

## Algorithms

- **Stochastic Gradient Descent (SGD)**: Basic gradient descent with stochastic updates.
- **Nesterov Accelerated Gradient (NAG)**: Advanced gradient descent method with momentum and lookahead.

### Loss Functions Implementations:
- **Ellipsoid**
- **Valley**
- **Himmelblau**

Each algorithm is implemented from scratch to demonstrate the core principles of optimization.

## Getting Started

Clone this repository to your local machine:

```bash
git clone https://github.com/yourusername/numpy-optimization-lab.git
cd numpy-optimization-lab
```

## Install Dependencies
The only external dependency is NumPy. You can install it using:

```bash
pip install numpy
```

## Running Examples
Each optimization algorithm and loss function is implemented in separate scripts. You can explore these implementations by running:

```bash
python sgd_example.py
python nesterov_example.py
```

For visualizations and 3D plotting of optimization paths, you may need matplotlib and plotly:

```bash
pip install matplotlib plotly
```

## Visualizing Optimization Paths
This repository includes various loss surfaces such as the Ellipsoid, Valley, and Himmelblau functions. Optimization paths are visualized in 3D, so you can easily track the progression of each optimization algorithm across these surfaces.

### Examples
Below are some example visualizations for the Nesterov Accelerated Gradient (NAG) algorithm on the Himmelblau loss function:

Each figure demonstrates the path the optimizer follows, highlighting the starting point, intermediate points, and the final convergence.

### Contributing
Contributions are welcome! If you'd like to contribute improvements, optimizations, or new algorithms to the repository, please feel free to fork the project and create a pull request.

### License
This project is licensed under the MIT License - see the LICENSE file for details.
