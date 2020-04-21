[//]: # (Image References)

[image1]: ./images/sample_dog_output.png "Sample Output"
[image2]: ./images/vgg16_model.png "VGG-16 Model Layers"
[image3]: ./images/vgg16_model_draw.png "VGG16 Model Figure"


## Project Overview
This project is part of <b>Udacity Deep Learning Nanodegree</b>.
In this project I completed following Tasks:
1. Build a human face detector using opencv Haarcascades.
2. Detect Dog breed directly using VGG16 pre trained model.
3. Building a CNN model from scratch for dog breed Classfications. (Total 133 dog breed classes).
4. Building a CNN model using transfer learning and re training it. 
5. Building a run_app function which takes image as input and output whether there is human or dog is present in image or not.
	--> If human is present the function returns resembling dog breed.
	--> If dog is present the function returns the predicted dog breed.
	--> If any other object is present it produces error.

![Sample Output][image1]


## Dataset

1. Download the [dog dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip).  Unzip the folder and place it in the repo, at location `path/to/dog-project/dogImages`.  The `dogImages/` folder should contain 133 folders, each corresponding to a different dog breed.
2. Download the [human dataset](http://vis-www.cs.umass.edu/lfw/lfw.tgz).  Unzip the folder and place it in the repo, at location `path/to/dog-project/lfw`.  If you are using a Windows machine, you are encouraged to use [7zip](http://www.7-zip.org/) to extract the folder. 
