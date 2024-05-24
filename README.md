FruitNet: AI-Based fruit detection and quality Analysis.

This project involves developing a system for fruit detection and quality analysis using Convolutional Neural Networks (CNNs) and image processing techniques. The key components of the project are as follows:

1. Dataset Sources: 
   - The datasets for training and testing the model are sourced from ImageNet and Kaggle, which are well-known repositories for machine learning and computer vision datasets.

2. Background Subtraction:
   - The GrabCut algorithm is employed to perform background subtraction. This algorithm helps in separating the fruit from the background, making it easier for the model to focus on the relevant features of the fruit.

3. Data Augmentation:
   - Various image transformations such as scaling, shearing, and linear transformations are applied to increase the dataset size and variability. This step is crucial for enhancing the model's generalization capabilities.

4. Model Training:
   - The models are built and trained using Keras and TensorFlow, which are popular libraries for deep learning. These libraries provide tools for building and training neural networks efficiently.
     
5. Performance Metrics:
   - The model achieves a training accuracy of 94.11% and a testing accuracy of 96.4%, indicating good performance on both the training and testing datasets.
