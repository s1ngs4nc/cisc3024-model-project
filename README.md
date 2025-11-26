# cisc3024-Pattern-Recognition-Project
# Handwritten Digit Generation with Diffusion Models

[![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white)](https://pytorch.org/)
[![Python](https://img.shields.io/badge/python-3.12+-blue.svg)](https://www.python.org/)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

A PyTorch implementation of diffusion models for generating handwritten digits from the MNIST dataset, featuring classifier-free guidance for conditional generation.

![Generated Digits](https://via.placeholder.com/600x200/4A90E2/FFFFFF?text=Generated+Handwritten+Digits)

## 📋 Project Overview

This project implements a state-of-the-art diffusion model capable of generating high-quality handwritten digits (0-9) using the MNIST dataset. The model leverages modern deep learning techniques including:

- **Diffusion Models**: Forward and reverse diffusion processes
- **Classifier-Free Guidance**: Conditional generation with label guidance
- **UNet Architecture**: Advanced neural network with attention mechanisms
- **Comprehensive Evaluation**: IS and FID metrics for quality assessment

## 🚀 Features

- ✅ Conditional generation of digits 0-9
- ✅ Classifier-free guidance for improved sample quality
- ✅ Training and evaluation pipelines
- ✅ Inception Score (IS) and Fréchet Inception Distance (FID) metrics
- ✅ Visualization of denoising process
- ✅ Configurable hyperparameters
- ✅ GPU acceleration support

## 📁 Project Structure
CISC3024-Diffusion-MNIST/
├── Cisc3024.ipynb # Main Jupyter notebook with full implementation
├── README.md # Project documentation
├── requirements.txt # Python dependencies
├── outputs/ # Generated samples and model checkpoints
└── data/ # MNIST dataset

## 🛠 Installation

### Prerequisites
- Python 3.12
- PyTorch 1.24
- CUDA-capable GPU (recommended)

### Setup
```bash
# Clone repository
git clone https://github.com/s1ngs4n/cisc3024-model-project.git
cd cisc3024-model-project

# Install dependencies
pip install -r requirements.txt

# For CUDA support (if available)
conda install pytorch torchvision torchaudio pytorch-cuda=12.4 -c pytorch -c nvidia
