# Diffusion-DDPM-  

Welcome to the **Diffusion-DDPM** project! This repository implements a **Denoising Diffusion Probabilistic Model (DDPM)**, a state-of-the-art generative model known for producing high-quality images through a diffusion process. This project is designed to provide a comprehensive understanding of diffusion models and their implementation using PyTorch.  

Dataset:  
![image](https://github.com/user-attachments/assets/25e461f9-af54-48c2-b4e0-6dbfe07d3740)  

Results:  
![image](https://github.com/user-attachments/assets/ad8ae1d8-b661-4a1e-9506-7d814943ba50)  
(28th epoch)  

## Features

- **DDPM Implementation**: A clear and concise implementation of the Denoising Diffusion Probabilistic Model.
- **Flexible Architecture**: Modular design allows easy modification and extension of the model.
- **Data Augmentation**: Built-in support for data augmentation techniques to enhance model training.
- **Customizable Training**: Easy configuration of hyperparameters and training settings.
- **Image Generation**: Generate high-quality images from random noise.
- **Noise Testing**: Evaluate the model's performance in noise reduction.
```bash
Diffusion-DDPM/
├── README.md               # Project overview and documentation
├── ddpm.py                 # Main script for training the DDPM model
├── ddpm_unconditionally.py  # Script for unconditional image generation
├── modules.py              # Contains the model architecture and layers
├── noise_test.py           # Test various noise levels and their impact on image quality
├── utils.py                # Utility functions for data processing and augmentation
└── requirements.txt        # Python package dependencies
```

## Installation

To get started with the **Diffusion-DDPM** project, follow these steps:

**Clone the Repository**:
   ```bash
   git clone https://github.com/bibasrairockz/Diffusion-DDPM.git
   cd Diffusion-DDPM
   ```  
## Usage
To use the Diffusion-DDPM model, you can run the training or generation scripts provided. Here’s a basic example of how to train the model:

```bash
python ddpm.py --dataset_path <path_to_your_dataset> --batch_size <your_batch_size>
```

## For image generation:

```bash
python ddpm_unconditionally.py --model_path <path_to_your_model>
```
Make sure to replace <path_to_your_dataset> and <path_to_your_model> with the actual paths on your system.
   



