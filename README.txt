### Google Landmark Recognition Challenge 2018
### Author: Rajan Patel

### Software and Libraries Required

Software: Jupyter Notebook with Python 3.6
Libraries: Numpy, Keras, Pandas, Glob, Matplotlib

### Implementation: Step by Step

## Step 1 : Download the dataset

Copy and paste the link below to access the dataset shared through Google Drive.
https://drive.google.com/open?id=11jTLYxxp8VCx_qmum7uMccKJmo9nlu_3

The dataset contains three subfolders:
1) train - contains 15270 training images
2) test - contains 3273 testing images
3) valid - contains 3273 validation images

The dataset also have three .csv files which contains the landmark ids and the source link from where the image was downloaded. 

## Step 2 : Calculate bottleneck features

Use following Jupyter Notebooks to calculate bottleneck features of different pre-trained models:
1) For VGG-16 model - bottleneck_features_vgg16.ipynb
2) For VGG-19 model - bottleneck_features_vgg19.ipynb
3) For ResNet model - bottleneck_features_resnet.ipynb

Note: Each file should be run with train, test, valid dataset separately to obtain respective bottleneck features. Depending on the system configuration, it may take long time to compute these features.

## Step 3 : Train the model

After calculating bottleneck features and saving them in .npz files, run the "Landmark_Classifier - test.ipynb" notebook file to train the model and test them with testing dataset.




