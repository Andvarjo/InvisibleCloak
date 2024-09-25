# Invisible Cloak 👁️‍🗨️
## Make Yourself Invisible in Real Time Using Deep Learning

Are you ready to feel like Harry Potter? 🧙‍♂️ This project aims to make a person disappear from a camera frame in real time using advanced segmentation and masking algorithms.

## Project Overview

This project leverages YOLOv8's models, trained on the COCO dataset, to perform segmentation and detect the presence of a person in the frame. Unlike traditional green screen techniques, which rely on color comparison to eliminate or add elements in the frame, our approach utilizes segmentation combined with a pre-recorded video of the background to effectively remove any person from the scene.

## Requirements

To run this project, you'll need the following:

- A CUDA-capable NVIDIA GPU (the project has been tested on an RTX 3070 Ti and performs excellently).
- CUDA must be configured on your local machine (please note that Google Colab does not support this unless you opt for a paid plan).

### Local Setup

You will need to install and compile OpenCV with CUDA on your local machine. Here are the necessary components:

1. Visual Studio 2019
2. CUDA Toolkit 12.2
3. cuDNN
4. CMake
5. OpenCV (including the binary files)
6. OpenCV Contrib
7. Anaconda

### Installation Reference

For a detailed installation guide, please refer to this [YouTube tutorial](https://www.youtube.com/watch?v=d8Jx6zO1yw0).

