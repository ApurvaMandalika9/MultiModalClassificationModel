# MultiModalClassificationModel

This project aims to develop a fusion model for multi-modal data classification, combining both image and audio information. 

The dataset consists of MNIST images and corresponding audio samples. 
Two separate models are utilized for image and audio data:
1. A Convolutional Neural Network (CNN) for images
2. An Artificial Neural Network (ANN) for audio.

The fusion model integrates the outputs of these two models through a fusion layer, enabling joint classification. 

Training involves optimizing the fusion model using Adam optimizer and Cross Entropy Loss. Experimentation with various hyperparameters such as filter size, number of filters, and learning rate was conducted to find the best configuration. 

The fusion model achieves the highest accuracy of 98.92% on the validation set, demonstrating the effectiveness of combining image and audio modalities for classification tasks.
