# Brain Tumor MRI Classification using CNN

A basic Convolutional Neural Network (CNN) built with PyTorch to classify brain MRI images into four categories: Glioma, Meningioma, Pituitary, and No Tumor.

## Dataset

**Brain Tumor MRI Dataset (Version 5)**

- Source: [Mendeley Data](https://data.mendeley.com/datasets/zwr4ntf94j/5)
- DOI: [10.17632/zwr4ntf94j.5](https://doi.org/10.17632/zwr4ntf94j.5)
- Total Images: 12,064
- Modality: T1-weighted contrast-enhanced MRI
- Image Format: JPEG
- Split: 80% Training, 20% Testing

### Classes

1. Glioma
2. Meningioma
3. Pituitary
4. No Tumor

## Model Architecture

A custom CNN implemented using PyTorch, consisting of:

- 3 Convolutional layers
- ReLU activation functions
- Max Pooling layers
- Fully Connected layers
- Adam optimizer
- Cross Entropy Loss

## Preprocessing

- Resize images to 64 × 64 pixels.
- Convert images to tensors.
- Apply random horizontal flipping and rotation to training images.

## Training and Evaluation

- Training for 15 epochs.
- Monitor training loss and accuracy.
- Evaluate the trained model using final test accuracy.

## Technologies

- Python
- PyTorch
- Torchvision
- Matplotlib

## License and Citation

The dataset is distributed under the CC BY 4.0 license. Please cite the original dataset when using it.

**Dataset:** *Brain Tumor MRI Dataset (Glioma, Meningioma, Pituitary, No Tumor)*, Mendeley Data, Version 5 (2025). DOI: [10.17632/zwr4ntf94j.5](https://doi.org/10.17632/zwr4ntf94j.5).