# Stable Diffusion Architecture

## Overview

PyTorch implementation of Stable Diffusion, including various components such as 
-Variational Autoencoder 
-Clip Encoder 
-Unet Architecture 
-Decoder, Latent Diffusion Models 
-Text-to-Image, Image-to-Image based Prompts
-Neural Inpainting.

## Features

- **Variational Autoencoder (VAE):** Implementation of a VAE for effective dimensionality reduction and generative modeling.
- **Clip Encoder:** Encoder part of the CLIP model, allowing for joint understanding of images and text.
- **Unet:** Implementation of the U-Net architecture for image segmentation tasks.
- **Decoder:** Model for generating realistic images from latent representations.
- **Latent Diffusion Models:** Implementation of Stable Diffusion models with simplified math as defined in the DDPM paper.
- **Text-to-Image:** Capability to generate images from textual descriptions.
- **Image-to-Image:** Ability to transform input images into new images.
- **Inpainting:** Reconstruction of images with missing or damaged parts.

## Getting Started

### Prerequisites

- Python 3.9+
- PyTorch


### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Samueal07/Stable_Diffusion_Architecture.git
   cd Stable_Diffusion_Architecture
