# stenosis-detection

This repository contains a two-stage deep learning pipeline for the detetion and localization of stenosis (narrowing of arteries) in coronary angiograms.The system leverages state-of-the-art computer vision architectures—**EfficientNet** and **YOLOv9**—enhanced with attention mechanisms to provide accurate classification and localization of stenotic regions.

- **Two-stage pipeline**:
  1. **Classification**: Identifies whether stenosis is present using EfficientNetB3.
  2. **Localization**: If stenosis is detected, YOLOv9c localizes the region using bounding boxes.

- **Attention-Enhanced Models**: Integrates the **CBAM (Convolutional Block Attention Module)** to improve model focus on relevant image features.

- **Dataset**: Utilizes the **ARCADE** dataset, a publicly available set of coronary angiography images.

- **Performance**:
  - **Localization Accuracy**: ~80.67% on a test set of 300 images.


