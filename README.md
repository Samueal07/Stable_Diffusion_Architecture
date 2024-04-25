# Stable Diffusion Architecture

## Overview
![image](https://github.com/Samueal07/Stable_Diffusion_Architecture/assets/99087302/7260eca3-6bc0-41f2-9d5d-ca5542c20c6f)


PyTorch implementation of Stable Diffusion, including various components such as 
-Variational Autoencoder 
![image](https://github.com/Samueal07/Stable_Diffusion_Architecture/assets/99087302/70b09e8b-0dfd-47d6-989a-1576a6058c84)

-Clip Encoder
![image](https://github.com/Samueal07/Stable_Diffusion_Architecture/assets/99087302/86633889-8f8b-40d9-8114-4b46b149e2d3)

-Unet Architecture 
![image](https://github.com/Samueal07/Stable_Diffusion_Architecture/assets/99087302/478a396a-d1a3-46a0-ac51-651377bb06e6)

-Decoder, Latent Diffusion Models 
-Text-to-Image based Prompts


## Features

- **Variational Autoencoder (VAE):** Implementation of a VAE for effective dimensionality reduction and generative modeling.
- **Clip Encoder:** Encoder part of the CLIP model, allowing for joint understanding of images and text.
- **Unet:** Implementation of the U-Net architecture for image segmentation tasks.
- **Decoder:** Model for generating realistic images from latent representations.
- **Latent Diffusion Models:** Implementation of Stable Diffusion models with simplified math as defined in the DDPM paper.
- **Text-to-Image:** Capability to generate images from textual descriptions.

## Getting Started

### Prerequisites

- Python 3.9+
- PyTorch


### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Samueal07/Stable_Diffusion_Architecture.git
   cd Stable_Diffusion_Architecture
