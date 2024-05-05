# YogaPose-Xception
Yoga Pose Detection/Classification using Xception Neural Network

Implementation of Xception (a Convolutional Neural Network variant) -architecture for yoga pose detection and classification. The dataset comprises five folders, each representing a yoga pose: 'Downdog', 'Goddess', 'Plank', 'Tree', and 'Warrior2'. Images were resized to 256 X 256 pixels. Transfer learning is utilized  by loading the pre-trained Xception model with ImageNet weights and excluding the fully connected layers (include_top=False). The model achieved a test accuracy of 90.91%, with the highest train accuracy recorded at 95.99%.
