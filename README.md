# Super_Resolution_GenAI

Welcome to the **Super_Resolution_GenAI** repository! This project focuses on applying super-resolution techniques using TensorFlow and TensorFlow Hub to enhance the quality of images. By utilizing the ESRGAN model, the project aims to transform low-resolution images into high-resolution counterparts without losing detail.

## Project Overview

**Super_Resolution_GenAI** uses the ESRGAN model (Enhanced Super-Resolution Generative Adversarial Networks) from TensorFlow Hub to upscale images. The system preprocesses images to fit the model requirements and applies advanced super-resolution techniques to produce detailed, high-quality images.

## Features

- **Image Upscaling**: Enhances low-resolution images to high-resolution using a pre-trained ESRGAN model.
- **Image Preprocessing**: Adjusts image sizes and formats to be compatible with the super-resolution model.
- **Display and Save Options**: Provides functionality to display both original and super-resolved images and an option to save the output.

## Methodology

1. **Image Loading and Preprocessing**: Images are loaded and preprocessed to match the input requirements of the ESRGAN model. This includes resizing and normalizing the images.
2. **Super-Resolution Transformation**: The preprocessed images are passed through the ESRGAN model to enhance their resolution.
3. **Visualization and Saving**: The results can be visualized directly in the interface, and there is an option to save the enhanced images for further use.

This system is designed to be a useful tool for both professionals and hobbyists looking to improve image quality for various applications such as digital art, photography, and scientific imaging.
