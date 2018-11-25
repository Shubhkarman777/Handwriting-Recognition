# Handwriting-Recognition
Developed a neural network to recognize handwritten document and convert it into text document. After this, the text document is checked for plagiarism.

About the notebooks:

1. Image Segmentation: In this notebook the handwritten document image is given as an input and at the end of the notebook the document gets segmented into characters and all the characters are cut down into different different images and are saved in a folder.
2. Character Recognition: In this notebook the model(convolutional neural network) is trained on IAM handwriting dataset. The folder of images obtained from 1st notebook passed to this model as input. This model then recognize those characters and give the output corresponding to those images in text form.

