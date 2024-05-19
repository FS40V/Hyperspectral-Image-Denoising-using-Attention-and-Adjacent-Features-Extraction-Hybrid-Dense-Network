AAFHDN: Hyperspectral Image Denoising
Project Overview
This project introduces a novel denoising algorithm for hyperspectral images (HSIs) called Attention and Adjacent Features - Hybrid Dense Network (AAFHDN). HSIs are prone to various types of noise due to the complexity of the imaging environment, corruption, and degeneration. While natural image denoising methods have been successful, existing CNN-based methods for HSIs face challenges in noise suppression and feature extraction.

Key Features
High-Frequency Feature Decomposition: Effectively separates high-frequency noise from essential image features.
Geometrical Characteristics Preservation: Maintains the structural integrity of images using structure priors.
Band Correlation Extraction: Utilizes the correlation of adjacent spatial and multiscale separable spectral features for improved feature extraction.
Methodology
AAFHDN leverages attention mechanisms and dense network structures to enhance the denoising process. The algorithm decomposes high-frequency features, preserves important geometrical characteristics, and extracts band correlations. This approach ensures better noise suppression and feature retention compared to traditional methods.

Experimental Results
The effectiveness of AAFHDN has been evaluated through comprehensive experiments on both simulated and real-world noisy images. Results demonstrate that AAFHDN significantly outperforms existing traditional methods in both quantitative evaluations and visual effects. The improved denoising performance of AAFHDN benefits subsequent classification and target detection tasks in HSIs.

Conclusion
AAFHDN represents a significant advancement in the field of HSI denoising, offering enhanced noise suppression and feature extraction capabilities. This algorithm has the potential to improve the accuracy of high-level semantic tasks in HSIs, such as classification and target detection.
