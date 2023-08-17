# Real-world Underwater Image Enhancement Algorithms
In this document, we provide a brief overview of the algorithms used for underwater image enhancement, as mentioned in the paper titled "Real-world Underwater Enhancement: Challenges, Benchmarks, and Solutions under Natural Light" by Risheng Liu, Xin Fan, Ming Zhu, Minjun Hou, and Zhongxuan Luo.

## Table of Contents
1. Introduction
2. CLAHE (Contrast Limited Adaptive Histogram Equalization)
3. MSRCR (Multi-Scale Retinex with Color Restoration)
4. DCP (Dark Channel Prior)
5. Dataset
6. Conclusion

### 1. Introduction
Underwater images often suffer from quality issues like reduced contrast, color cast, and low visibility due to light absorption and scattering. The following algorithms aim to address these problems and enhance the overall quality of underwater images.

### 2. CLAHE (Contrast Limited Adaptive Histogram Equalization)
CLAHE is a popular technique for improving the contrast of an image. Unlike global histogram equalization, which applies a singular transformation to the entire image, CLAHE works by dividing the image into smaller sections and applying histogram equalization to each of them. This prevents over-enhancement and noise amplification.

### 3. MSRCR (Multi-Scale Retinex with Color Restoration)
MSRCR is based on the Retinex theory, which suggests that the observed image can be decomposed into illumination and reflectance. MSRCR uses this theory to operate on multiple scales to account for varying sizes of details in the image. Additionally, it introduces a color restoration step to maintain color accuracy.

### 4. DCP (Dark Channel Prior)
DCP is based on the observation that, in outdoor haze-free images, at least one color channel has low intensity in most patches. In underwater scenarios, the dark channel can help estimate the scene depth and further refine the haze model.

### 5. Dataset
The reference paper uses a dataset of real-world underwater images. This dataset provides a collection of diverse underwater scenes taken under natural light conditions, ensuring a practical benchmark for evaluating the enhancement algorithms.

### 6. Conclusion
Enhancing underwater images is essential for various applications, including marine biology, underwater archaeology, and recreational photography. While each algorithm has its strengths and weaknesses, the choice of the best one depends on the specific characteristics and requirements of the given image.

### References
Real-world Underwater Enhancement: Challenges, Benchmarks, and Solutions under Natural Light, Risheng Liu et al., IEEE.
Please note that the above information is a brief summary of the topic. For in-depth details and understanding, it's essential  to refer to the original paper and related resources.
