# <h1 align="center">Pix2Pix</h1>

<p align="center">
<img src="images/image_readme.png"> 
</p>
<p align="center"><i>Source: TensorFlow</i></p>

This repository implements generative models inspired by the paper [*Image-to-Image Translation with Conditional Adversarial Networks*](https://arxiv.org/abs/1611.07004) by Isola et al. (2017), also known as Pix2Pix. This method offers a powerful framework for image translation tasks, enabling the direct mapping from input to output images based on paired training data. Pix2Pix has demonstrated remarkable results in various applications, including style transfer, semantic segmentation, and image synthesis.

## TensorFlow and PyTorch Implementations

To explore the capabilities of Pix2Pix, implementations were done in both TensorFlow and PyTorch, the two most widely used frameworks in Deep Learning. Each implementation provides deep insights into the differences and similarities between these frameworks, offering practical perspectives for deep learning practitioners.

- [TensorFlow Notebook](Pix2Pix_Satellite2Routes_TensorFlow.ipynb)

- [PyTorch Notebook](Pix2Pix_Satellite2Routes_Pytorch.ipynb)

## Dataset Setup

The ``Satellite2Route`` dataset was utilized, comprising directories of satellite aerial images (input) and map routes (output). Access to the dataset is available either through direct download or via access from [my Personal Drive](https://drive.google.com/drive/folders/19giwoxuUnRg0-5cB9SJS7ETY9fmuBOgd?usp=sharing).

## Key Components of Pix2Pix

Among the crucial aspects of Pix2Pix are:

- **Generator Architecture:** A generator architecture based on [U-Net](https://arxiv.org/abs/1505.04597) is implemented, renowned for its effectiveness in image generation tasks.
- **PatchGAN Discriminators:** Inspired by the [pix2pix paper](https://arxiv.org/abs/1611.07004), PatchGAN discriminators are used to evaluate the authenticity of generated images at a patch level, providing detailed feedback.

## Generated Examples

<p align="center">
<img src="images/satellites_to_routes.gif"> 
</p>

The generated examples and GIF of the results are located in the [images folder](images), with additional examples available in the notebooks.

## Technological Stack
[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white&labelColor=101010)](https://docs.python.org/3/) 
[![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white&labelColor=101010)](https://www.tensorflow.org/api_docs)
[![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white&labelColor=101010)](https://pytorch.org/docs/stable/index.html)

## Contact
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white&labelColor=101010)](mailto:jerson.gimenesbeltran@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=101010)](https://www.linkedin.com/in/jerson-gimenes-beltran/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white&labelColor=101010)](https://github.com/JersonGB22/)