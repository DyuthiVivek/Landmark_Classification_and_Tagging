# Landmark_Classification_and_Tagging

### Created a custom Convolutional Neural Network (CNN) from scratch for landmark classification

Started with an initial Conv2d layer, progressively increasing filters while maintaining 3x3 kernels. ReLU activations and BatchNorm layers were added for non-linearity and normalization. MaxPooling layers were used to downsample the feature maps. Dropout was used to prevent overfitting.

### Implemented a second CNN using Transfer Learning to benchmark various pre-trained models

Chose ResNet-18 due to its proven performance and efficiency in various image classification tasks. Since ResNet18 was trained for the ImageNet task, it is a good choice for landmark classification tasks.

