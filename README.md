# Eyes Disease Classifier

## Overview

This project builds a Deep Learning model to classify eye diseases based on images. The model utilizes the **MobileNetV2** architecture, pre-trained on ImageNet (Transfer Learning), to achieve high efficiency with low computational cost.

## Dataset

The dataset consists of images categorized into 6 classes:

1.  **Cataract**
2.  **Diabetic Retinopathy**
3.  **Glaucoma**
4.  **Healthy**
5.  **Macular Scar**
6.  **Myopia**

The data is split into a training set (80%) and a validation set (20%) using `ImageDataGenerator`.

## Technologies Used

- **Python**
- **TensorFlow / Keras**: Main framework for building and training the model.
- **MobileNetV2**: Base model for Transfer Learning.
- **Matplotlib**: Data visualization and result plotting.
- **NumPy**: Array processing and numerical computing.

## Training Configuration

- **Image Size**: 256x256
- **Batch Size**: 32
- **Data Augmentation**:
  - Rotation range: 30
  - Width/Height shift: 0.2
  - Shear range: 0.2
  - Zoom range: 0.3
  - Horizontal/Vertical flip
  - Brightness range: [0.5, 1.5]

## Usage

1.  Install the required libraries:
    ```bash
    pip install tensorflow numpy matplotlib pillow
    ```
2.  Open the notebook `Eyes_Disease_Classifier.ipynb`.
3.  Update the data path (`data_path`) if necessary.
4.  Run the cells in the notebook to train and evaluate the model.

## Author

- Group 1 - Advanced AI Topic 2
