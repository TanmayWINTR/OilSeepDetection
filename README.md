# Oil Seep Detection: A Computer Vision Tool

## Overview
Welcome to the Oil Seep Detection repository. This project is a computer vision tool designed to detect and classify oil seeps in satellite images using a custom U-Net model with an Xception backbone. The tool effectively segments and identifies seeps in large datasets of satellite imagery, which is crucial for environmental monitoring and resource management.

## Understanding Oil Seep Detection
Oil seep detection involves identifying areas where oil naturally leaks to the Earth's surface, typically in the ocean or on land. These seeps can be indicators of underwater oil reserves or environmental pollution. Detecting oil seeps is essential for understanding natural oil leakage, assessing environmental impacts, and aiding in the exploration of oil reserves.

## Dataset
The dataset includes satellite images and their corresponding masks. Each image is 256x256 pixels, with each pixel classified as non-seep (0) or one of seven classes of seeps (1-7). The masks highlight the seep areas within the images.

**Note:** The dataset is not included in this repository. To obtain access, please contact me directly.

## Model Architecture
The model utilizes a U-Net architecture with an Xception backbone, combining powerful feature extraction and segmentation capabilities.

### Key Components:
- **Convolution Blocks:** Extract hierarchical features from images.
- **Residual Blocks:** Mitigate the vanishing gradient problem, enhancing learning.
- **Encoder:** Downsamples the spatial dimensions, increasing feature depth.
- **Decoder:** Upsamples to reconstruct the spatial dimensions for detailed segmentation.

## Visual Results
The tool has shown strong performance in identifying oil seeps, with effective learning during training and accurate predictions on validation data. Visual comparisons of the predicted masks against true seep locations demonstrate the model's practical utility.

## Contact
For any questions or to request access to the dataset, please contact me at [reply2tanmayv@gmail.com].

Thank you for your interest in the Oil Seep Detection project! Your feedback and contributions are welcome.
