# Car-classification
Used ResNet50 to classify the car images.

# About resnet50:
This is a pretrained model on thousands of images. So we can use the weights of this model to solve our own problem. Basically ResNet50 have the thousand output nodes at the end which classifies the thousand class. But in our case we only have three classes of cars. So we remove the output layer of this network which classifies the 1000 class and add our own output layer which consist of only 3 nodes. 
