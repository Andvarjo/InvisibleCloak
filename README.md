# InvisibleCloak👁️‍🗨️
## Invisible cloak in real time using DL. want to feel like Harry Potter? 🧙‍♂️
The purpose of this project is to make a person disappear from a camera frame in real time using segmentation and masking algorithms.

Using yolov8's motos that is trained with the coco dataset, we perform segmentation to detect whether or not there is a person in the frame.

This technique is different from that used with the green screen background, which compares colors to eliminate or generate new elements in the frame. Using segmentation and a previously captured video of the background we can eliminate any person from the frame

# Requirements:

need CUDA able Nvida GPU ( used with RTX3070TI and runs excellent)
you must be able to use CUDA in your local machine (colab is not capable to perform this unless you pay )

you must install and compile openCV with cuda iin your local machine:
*  visual studio 2019
*  cuda toolkit 12.2
*  cudnn
*  cmake
*  opencv bin
*  opencv_contrib
*  anaconda

### link for reference installation: https://www.youtube.com/watch?v=d8Jx6zO1yw0
