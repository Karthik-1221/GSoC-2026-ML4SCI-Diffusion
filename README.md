# GSoC 2026: Diffusion Models for Fast CMS Simulation
**Candidate:** Karthik Boodidha  
**Organization:** ML4SCI (Machine Learning for Science)  
**Project:** Diffusion models for fast and accurate simulations of low level CMS experiment data

## Project Overview
This repository contains the technical test task for GSoC 2026. The goal is to implement a **Denoising Diffusion Probabilistic Model (DDPM)** to simulate particle detector data, providing a faster alternative to Monte Carlo simulations.

## Important Note on Dataset Access
During the application window, the primary CMS G25 dataset links (ml4sci.org/data/G25) returned **404 Not Found** errors. To demonstrate my technical competence and understanding of the diffusion process, I have implemented this **Proof of Concept (PoC) using the MNIST dataset**. 

The implementation includes:
* **Forward Diffusion:** Linear noise scheduling and Gaussian noise injection.
* **Reverse Diffusion:** A PyTorch-based denoising architecture.
* **Statistical Validation:** A "Creative" sparsity comparison test to verify physical consistency between real and generated samples.

## How to Run
1. Open the `.ipynb` file in Google Colab.
2. Enable T4 GPU.
3. Run all cells to see the training loop and generated plots.

## Technologies Used
* **Python**
* **PyTorch**
* **Matplotlib / NumPy**
