# GradCam Visualization

Here I performed a mahine learning visualization named as gradcam. The dataset is on a classification problem, which consists of 6 classes of image. The classes are    
+ building
+ forest
+ glacier
+ mountain
+ sea
+ street     

Now after performing some image augmentation I made a resnet model which has 19M trainable parameter. 
 

First of all a model is created using CNN. Then using GradCam trying to analysis why model predicted that, which section of our model leads the prediction, what is  the contribution of all portion of the image.    
The dataset and source code in python is given. Data is divided for training and testing. Some theory is also added, related to CNN and GradCam.
