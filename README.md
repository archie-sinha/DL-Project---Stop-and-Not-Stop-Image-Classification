# DL-Project---Stop-and-Not-Stop-Image-Classification
This project aims to develop a deep learning-based classifier to distinguish between images of stop signs and non-stop signs. Utilizing a combination of data augmentation, transfer learning, and clustering techniques, the project addresses the challenge of correctly identifying stop signs in diverse and complex real-world street scenes.


# Stop and Not Stop Sign Classification DL Project
This project aims to develop a deep learning-based classifier to distinguish between images of stop signs and non-stop signs. Utilizing a combination of data augmentation, transfer learning, and clustering techniques, the project addresses the challenge of correctly identifying stop signs in diverse and complex real-world street scenes.

Initially, the dataset comprises images of stop signs and non-stop signs. Data augmentation techniques such as rotation, scaling, and flipping are applied to the images to enhance the model's robustness and generalisation capability, effectively increasing the dataset size and diversity.

The project leverages a pre-trained convolutional neural network (CNN) model, VGG16, trained on a large-scale image dataset (ImageNet). This pre-trained model is used for feature extraction due to its proven ability to capture high-level image features effectively. The extracted features are then fine-tuned using a small set of additional layers to adapt the model specifically for the task of classifying stop signs versus non-stop signs.

The features extracted from the images are clustered using the K-Means algorithm for classification. This unsupervised learning method groups the features into two clusters, corresponding to stop signs and non-stop signs.

Finally, the model's performance is evaluated by testing it on new images, including those previously misclassified, to ensure its accuracy and reliability in correctly identifying stop signs. The project demonstrates the potential of combining transfer learning and data augmentation to build a robust image classifier capable of performing well in real-world scenarios.
