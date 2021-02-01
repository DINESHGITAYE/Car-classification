# Car-classification
Used ResNet50 to classify the car images.

# About resnet50:
This is a pretrained model on thousands of images. So we can use the weights of this model to solve our own problem. Basically ResNet50 have the thousand output nodes at the end which classifies the thousand class. But in our case we only have three classes of cars. So we remove the output layer of this network which classifies the 1000 class and add our own output layer which consist of only 3 nodes. 

## Things that kept into mind while using the ResNet50:
1. We have to specify the size of the images (ex: [244,244])
2. We have to convert images into RGB format.
3. We have to add first layer and output layer manually
4. Do not trained the model weights again because its already have trained weights ('imagenet')
