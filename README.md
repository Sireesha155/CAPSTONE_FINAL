# CAPSTONE_FINAL

# Introduction
Image segmentation is a fundamental process in computer vision and image processing,
where an image is divided into distinct regions based on specific characteristics.
Traditional segmentation methods, such as Otsu’s and Kapur’s thresholding techniques,
primarily rely on pixel brightness to determine segmentation boundaries. However,
these methods often struggle with noisy images or images containing complex textures,
leading to inaccurate segmentation.
To overcome these challenges, this project explores a Two-Dimensional HistogramBased Bilevel Image Segmentation approach. Unlike conventional methods, this
technique considers not only the brightness of a pixel but also its relationship with
surrounding pixels through Local Contextual Information (LCI). By incorporating LCI,
the segmentation process captures contextual information, leading to more precise
results, especially in noisy environments and edge-detection scenarios.
This research aims to develop and analyze the proposed segmentation method by
comparing its performance with existing techniques. The study focuses on optimizing
the algorithm for improved segmentation accuracy, making it suitable for applications
such as medical imaging, defect detection, and remote sensing.
1.1Overview of the problem statement
Traditional thresholding methods in image segmentation primarily use brightness
information, leading to inaccurate segmentation, particularly in noisy or complex
images. To improve segmentation accuracy, it is necessary to account for the contextual
information between pixels. This project explores a new thresholding method that
constructs a two-dimensional histogram using the brightness of a pixel and the local
relative entropy Local Contextual Information (LCI). of its neighboring pixels. By
incorporating the LCI, which measures brightness differences between a pixel and its
neighbors, more accurate segmentation can be achieved.
1.2 Objectives and Goals
To develop an improved image segmentation method based on two-dimensional
histograms incorporating brightness and local relative entropy.
To compare the accuracy of the new method with traditional thresholding techniques
such as Otsu and Kapur.
To optimize the method for effective image segmentation in noisy environments.
