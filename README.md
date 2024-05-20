# Object-detection-and-localization
Detects, classifies and draws boundary boxes around numbers from an altered MNIST dataset. 

Unfortinatly, this project does not include any of the datasets, as the files are too big. All models except SkreNet is present, SkreNet was also unfortinatly too big. As the datasets is not included it is not possible to recreate the results.

In this notebook, two types of models are created. The first type can only handle empty images or images with one and only one number in the image. If the model detects an image is classifies it and draws a boundary box. The second type of model can handel images with multiple numbers per image, however in practice there are no more than three numbers per image. These models also draws boundary boxes around each of the numbers in the image.

SkreNet is one of the models that handels only one number, and SkreNet_2 can handle mulitple numbers
