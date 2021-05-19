# Image-Classification-of-COVID-19-X-rays

This is the class challenge for CS440 Fall 2020. 
In this class challenge, we will classify X-ray images. The data we will use has been collected by Adrian Xu, combining the Kaggle Chest X-ray dataset with the COVID-19 Chest X-ray dataset collected by Dr. Joseph Paul Cohen of the University of Montreal. The data can be downloaded here:
https://drive.google.com/file/d/1Y88tgqpQ1Pjko_7rntcPowOJs_QNOrJ-/view

When you extract the data you will have two folders: two that will be used for a binary classification task (Task1), and all that will be used for multi-class classification (Task2). An ipython notebook template is provided for each task.

Task1:
Train a deep neural network model to classify normal vs. COVID-19 X-rays using the data in the folder two. Starting from a pre-trained model typically helps performance on a new task, e.g. starting with weights obtained by training on ImageNet. After training is complete, visualize features of training data by reducing their dimensionality to 2 using t-SNE. If your extracted features are good, data points representing a specific class should appear within a compact cluster.

Task2:
Train a deep neural network model to classify an X-ray image into one of the following classes: normal, COVID-19, Pneumonia-Bacterial, and Pneumonia-Viral, using the folder all. Explore at least two different model architectures for this task, eg. AlexNet vs. VGG16. After training is complete, visualize features of training data by reducing their dimensionality to 2 using t-SNE. If your extracted features are good, data points representing a specific class should appear within a compact cluster.