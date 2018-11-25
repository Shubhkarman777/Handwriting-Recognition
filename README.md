# Handwriting-Recognition
Developed a neural network to recognize handwritten document and convert it into text document. After this, the text document is checked for plagiarism.

# Dataset
http://www.fki.inf.unibe.ch/databases/iam-handwriting-database
Visit this link to download the dataset.

# Pre-requisites
1. Python 3.4
2. Anaconda
3. Tensorflow 1.9.0
4. Numpy
5. Matplotlib
6. PIL
7. OpenCV

# About the jupyter notebooks:

1. Image Segmentation: In this notebook, the handwritten document image is given as an input and at the end of the notebook the document gets segmented into characters and all the characters are cut down into different different images and are saved in a folder.
2. Character Recognition: In this notebook, the model (convolutional neural network) is trained on IAM handwriting dataset. The folder of images obtained from 1st notebook passed to this model as input. This model then recognize those characters and give the output corresponding to those images in text form.
3. Handwriting Recognition(DataLoader): This iPython notebook simply explores how to load the handwriting dataset in preparation for training the model(three-layer recurrent neural network (LSTM cells)) on real handwriting data. 
First time use: download dataset from IAM Handwriting Database. There are two folders in this dataset that matter: 'ascii' and 'lineStrokes'. Put these in a './data' directory relative to this notebook. When an instance of this model is created for the first time it will parse all of the xml data in these files and save a processed version to a pickle file. This takes about 10 minutes but you only need to do it once.
