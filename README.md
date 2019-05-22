# Image-Search-Engine


The Image Search Pipeline is implemented by using VGG16,a pretrained model to do the feature extraction of the images of the whole dataset and then comparing the features of the query image,extracted by passing the image to the model with the features of all other images in the dataset.The comparison is done by using KDTree algorithm,and hence getting the 10 similar images to the query image.
