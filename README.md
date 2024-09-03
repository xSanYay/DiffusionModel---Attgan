# AttGan

# Diffusion Model Implementation

This repository contains the code for implementing a diffusion model using PyTorch within a GitHub Codespace. The model generates images based on a text prompt by leveraging a pre-trained model checkpoint.

## Installation

In your GitHub Codespace terminal, execute the following commands to set up the environment and install the necessary dependencies:

```bash
# Clone the repository
git clone --recursive https://github.com/crowsonkb/v-diffusion-pytorch

# Navigate into the directory
cd v-diffusion-pytorch

# Install dependencies
pip install git+https://github.com/crowsonkb/k-diffusion

# Download the diffusion model checkpoint
mkdir checkpoints
curl -L --http1.1 https://the-eye.eu/public/AI/models/v-diffusion/cc12m_1_cfg.pth > checkpoints/cc12m_1_cfg.pth

![image](https://github.com/user-attachments/assets/42d0ece5-35a1-465e-9ce4-d77cbc2dcf2d)

# Set your parameters
prompt = 'Dog playing'
weight = 5
n_images = 4
steps = 50
seed = 0



