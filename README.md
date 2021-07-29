# Binary-Classification-of-Scenery-Images

This project was to do a binary classification on scenery images downloaded from Kaggle. (dataset source: https://www.kaggle.com/puneet6060/intel-image-classification)

A convolution neural network with 3 convolutional layers and 2 fully-connected layers was used for binary classification.

The model attained an accuracy of 90% on the testing dataset (train/test ratio: 9:1)

### mydataset.ipynb

Defined a customized dataset used in this project.

### Test_Dataset.ipynb

Test whether the dataset successfully retrived batches of images.

### Test_model_layers.ipynb

Output the sizes of data after each convolutional or maxpooling layers to make sure the sizes passed into the first fully-connected layer is correct.

### mini_project_0728

Main notebook including model training and accuracy calculation.

### Create_csvfile.ipynb

Create a metadata .csv file from existing images. 

Column 1: image name retrieved from the image folder

Column 2: Labels that either 0 or 1 (0 represents 'sea' and 1 represents 'forest' in this project)
