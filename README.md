# Micrograd Neural Network Backpropagation

This repository contains an implementation of backpropagation using **Micrograd**, a lightweight autograd engine for neural networks.

## Overview
This Jupyter Notebook explores backpropagation by manually computing gradients and then automating the process using **Micrograd**. It covers:

- **Manual Gradient Calculation**: Step-by-step computation of derivatives for a simple function.
- **Backpropagation Implementation**: Applying chain rule principles for multi-variable differentiation.
- **Automatic Differentiation**: Leveraging Micrograd to compute gradients efficiently.
- **Neural Network Training**: Using backpropagation to update model parameters.

## Files
- `nn_backpropagation_micrograd.ipynb` - Notebook containing the backpropagation implementation and experiments.

## Prerequisites
Ensure you have the following dependencies installed:

```bash
pip install numpy matplotlib micrograd
```

## Running the Notebook
To execute the notebook:

1. Clone the repository:
   ```bash
   git clone https://github.com/panchaldhruv27223/Micro_grad.git
   ```
2. Navigate to the directory:
   ```bash
   cd Micro_grad
   ```
3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook nn_backpropagation_micrograd.ipynb
   ```

## Results
The notebook demonstrates how gradient calculations affect neural network training and how Micrograd simplifies this process. Visualization of gradients and parameter updates is included.

## References
- [Micrograd Repository](https://github.com/karpathy/micrograd)
- [Backpropagation Algorithm](https://en.wikipedia.org/wiki/Backpropagation)

## License
This project is released under the MIT License.

