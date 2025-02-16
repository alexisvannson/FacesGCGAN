# FacesGCGAN

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/alexisvannson/Deepfake/blob/main/FacesGCGAN.ipynb)

## Overview
**FacesGCGAN** is a deep learning project that uses **Generative Adversarial Networks (GANs)** for generating facial images.

For a detailed explanation of how GANs work, check out my article:  
[Generative Adversarial Networks Explained: Building AI-Generated Images](https://alexisvannson.hashnode.dev/generative-adversarial-networks-explained-building-ai-generated-images)

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/FacesGCGAN.git
   cd FacesGCGAN
   ```

2. Install the necessary dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. For Kaggle datasets, ensure you have a `kaggle.json` API key in place:

   ```python
   from google.colab import files
   files.upload()  # Upload kaggle.json

   !mkdir ~/.kaggle
   !cp kaggle.json ~/.kaggle/
   !chmod 600 ~/.kaggle/kaggle.json
   ```
