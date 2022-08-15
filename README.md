# Image-Denoising

Image denoising using different methods and comparing their results using SSIM and MSE

Image denoising is a significant challenge in image processing and computer vision, where the goal is to improve an image's quality by removing as much noise as possible. It's utilized in a variety of applications, including image classification, restoration, and visual tracking.

In this task I have made use of several denoising approaches, such as the Mean filter, Median filter, Wavelet Denoising, and any one of the open-source deep learning models, to achieve a denoised image. 

The input data consists of 25 photos with three distinct levels of noise: 10%, 25%, and 50%, as well as ground truth images. After that, different measures like the Structural SIMilarity (SSIM) index and Mean Squared Error are used to compare the denoised and ground truth images. These metrics are used for measuring the similarity between two images.

Below are the comparison results of the first 4 images in each level

![image](https://user-images.githubusercontent.com/101949683/184731261-01946b2a-9e97-4a38-b1cc-51438ac2d70a.png)


NOTE : The code is designed to compare and display only a few images from each category. Change the loop to compare all images.

> Copyright 2022 Rishil Darne
