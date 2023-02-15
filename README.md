# Denoising Image Processing

Image denoising is a fundamental image processing problem and the basis for a preprocessing step for many advanced computer vision tasks. Images are commonly used in people’s daily life and it is common to find an image with noise. This project studies denoising method on 25 images with three different level of noises, noise 10, noise 25 and noise 50 – the image dataset is provided from The Berkeley Segmentation Dataset by Mark et al. 

<p align="center">
  <img src="https://user-images.githubusercontent.com/82886152/219176285-447cb2b4-090c-43d8-885e-74577a34c93d.png">
</p>

The given images have Gaussian noise and, to remove this noise, Fast Fourier Transformation was executed to convert image into frequency so that Gaussian filter can be operated on the frequency domain instead of image. Furthermore, deconvolution technique was performed as a post-processing method to clear the blurred edges using Wiener filter.

Not only that, the performance of my denoising algorithm was compared with three existing methods such as Mean filter, Median filter and Wavelet denoising (VisuShrink). For assessment, mean squared error (MSE) and structural similarity (SSIM) score were generated.

The details can be found in the report uploaded in the repository and the code can be seen here: https://drive.google.com/file/d/1aqGdaf9iCoHD-P7SOekjiKCPlKiUkfwR/view?usp=sharing
