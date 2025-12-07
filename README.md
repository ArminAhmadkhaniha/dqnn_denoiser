# DQNN denoiser

[![DOI](https://img.shields.io/badge/DOI-10.1103%2FPhysRevA.109.032620-blue)](https://journals.aps.org/pra/abstract/10.1103/PhysRevA.109.032620)
[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com)
[![nbviewer](https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.svg)](https://nbviewer.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Overview

This repository contains the source code and simulation data for the paper **"Noisy intermediate-scale quantum computer–compatible error correction of quantum data using modified dissipative quantum neural networks"**, published in *Physical Review A*.

We propose a **Dissipative Quantum Neural Network (DQNN)** architecture that outperforms existing Quantum Autoencoders (QAE) in denoising tasks. By introducing conjugate layers and analyzing Renyi entropy during training, this model achieves high fidelity with significantly fewer parameters.

### Key Features
* **Architecture:** DQNN with conjugate layers for enhanced denoising.
* **Efficiency:** Reduced learning parameters compared to standard QAEs.
* **Robustness:** Capable of denoising unseen noisy data with different underlying noise distributions.
* **Analysis:** Includes code for analyzing the Renyi entropy of hidden/output qubits.

## Getting Started

### Prerequisites
The code is written in Python 3.10+ and relies on **PennyLane** and **TensorFlow**.

### Installation
To install dependencies:
```bash
pip install -r requirements.txt

```