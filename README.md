# Image-Segmentation
Getting started with Unstructured Datasets, Computer Vision and Deep Learning

# Image Segmentation Project

🌟 **Welcome to my Image Segmentation Project!** 🌟

## Overview

This repository encapsulates an in-depth exploration of Image Segmentation, marrying the latest computer vision techniques with the robust capabilities of OpenCV and TensorFlow. At the core of this endeavor lies the implementation of the U-Net Mobile Architecture, a highly efficient solution renowned for real-time image segmentation tasks. The architecture's compact design ensures optimal performance, making it particularly suitable for resource-constrained environments where real-time segmentation is paramount.

🚀 **Benefits of U-Net Mobile Architecture:**
- **Compact Design for Efficiency:** U-Net's architecture is tailored for real-time applications, striking an optimal balance between computational efficiency and accuracy.
- **Fine Detail Capture:** U-Net excels in capturing intricate details and complex structures, making it an ideal choice for high-resolution segmentation tasks.

## Implementation Details

The journey begins with meticulous image pre-processing, where OpenCV takes center stage. Tasks such as resizing, normalization, and color space conversion are meticulously executed to ensure that the original image's nuances are preserved. The critical process of flattening follows, reshaping the multi-dimensional image data into a format compatible with U-Net. TensorFlow, with its seamless integration and inherent optimization for handling high-dimensional data, proves to be superior in this regard compared to traditional libraries like scikit-learn.

🌐 **Image Pre-processing:**
The image pre-processing pipeline plays a pivotal role in preparing the data for segmentation. OpenCV facilitates tasks such as resizing to a standardized format, normalization for consistent pixel intensity, and color space conversion for optimal feature extraction. Preservation of information during this stage is critical to ensure that the model receives input that retains the original image's characteristics.

🔄 **Flattening of Images:**
Flattening represents a critical step in data preparation for U-Net. The reshaping of multi-dimensional image data into a suitable format preserves the spatial relationships essential for accurate segmentation. TensorFlow's capabilities shine in handling this high-dimensional data, offering superior performance in comparison to conventional alternatives like scikit-learn.

🔍 **Otsu Thresholding for Background-Foreground Differentiation:**
Within the pre-processing pipeline, Otsu's thresholding technique from OpenCV dynamically determines the optimal threshold, effectively distinguishing between background and foreground pixels. This adaptive thresholding method significantly enhances the accuracy of subsequent segmentation by providing a data-driven approach to differentiate between the two classes.

![image](https://github.com/soumya1107/Image-Segmentation/assets/64662510/ef7feaa7-7bf4-4c4d-a79b-2f6570132dd9)


In this equation, \( T \) represents the optimal threshold, while \( \sigma_B^2(t) \) and \( \sigma_F^2(t) \) denote the variances of the background and foreground, respectively, at threshold \( t \).

![image](https://github.com/soumya1107/Image-Segmentation/assets/64662510/e9b37733-0773-4c53-982b-9b21f50a966e)


🚀The (Background + Foreground) plotting for the Otsu thresholding method
![image](https://github.com/soumya1107/Image-Segmentation/assets/64662510/d4675a19-578a-4c64-8b98-c71842d63c8f)

🚀The Histogram plotting for Otsu Thresholding
![image](https://github.com/soumya1107/Image-Segmentation/assets/64662510/29265b1f-aee0-4aa4-9f65-72ac85599536)


Feel free to delve into the code, contribute to the project, and engage in the fascinating world of nuanced image segmentation! Your feedback and collaboration are invaluable. 🙌

🔗 **Dependencies:**
- OpenCV
- TensorFlow
- U-net mobile architecture
- Otsu Thresholding algorithm
- Numpy
- Pandas
- Matplotlib

📄 **License:** [MIT License](LICENSE)

📚 **References:**
- [U-Net: Convolutional Networks for Biomedical Image Segmentation](https://arxiv.org/abs/1505.04597)
- [Otsu's Method for Threshold Selection](https://ieeexplore.ieee.org/document/4310076)

Thank you for stopping by, looking to hear from you and imrpove! 
