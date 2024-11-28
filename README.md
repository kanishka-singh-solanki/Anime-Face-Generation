# Anime Face Generation using GAN
This project focuses on generating high-quality anime-style faces using Generative Adversarial Networks (GANs). It demonstrates how GANs can learn to create realistic, unseen images by training on a dataset of real anime faces.

## Project Overview
**Objective**: Generate anime faces using a GAN model.
**Dataset**: 63,000 real anime face images.
**Model**: Generative Adversarial Network (GAN) built using PyTorch.
**Results**: Achieved a fake score of 0.0009 and a real score of 0.9896.

## Key Features
Architecture: The GAN consists of a generator and discriminator. The generator creates new anime faces, while the discriminator distinguishes between real and generated images.
Training Process: The model was trained over multiple epochs to optimize both the generator and discriminator losses.
Performance Metrics: The model's ability to generate realistic images was validated using fake and real scores.

## Tech Stack
**Languages**: Python
**Libraries**: PyTorch, NumPy, Matplotlib
**Core Concepts**: Deep Learning, CNNs, GANs

How to Run
Clone the repository:
bash
Copy code
git clone https://github.com/kanishka-singh-solanki/Anime-Face-Generation.git
Install dependencies:
bash
Copy code
pip install torch torchvision numpy matplotlib
Run the Jupyter Notebook:
bash
Copy code
jupyter notebook AnimeGAN.ipynb

## Future Improvements
Train on a larger or more diverse dataset.
Experiment with different GAN architectures (e.g., DCGAN, StyleGAN).
Implement data augmentation techniques.

## References
[GAN Paper](https://arxiv.org/abs/1406.2661)
[Dataset source link](https://www.kaggle.com/splcher/animefacedataset)
