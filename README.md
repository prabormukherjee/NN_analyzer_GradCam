# GradCam Visualization

Here I performed a mahine learning visualization named as gradcam. The dataset is on a classification problem, which consists of 6 classes of image. The classes are    
+ building
+ forest
+ glacier
+ mountain
+ sea
+ street     

Now after performing some image augmentation I made a resnet model which has 19M trainable parameter. Then I trained the CNN model which has 86% acc on val set. Finally I visualized the activation map using Grad-Cam which basically tells us why the model has predicted the. It is a powerful way how model is evaluating the data. That analysis which section of our model leads the prediction, what is  the contribution of all portion of the image.    

The dataset and source code in python is given. Data is divided for training and testing. Some theory is also added in the notebook, related to CNN and GradCam.

### Extra Resources
Check *[ImageDataGenerator](https://www.tensorflow.org/api_docs/python/tf/keras/preprocessing/image/ImageDataGenerator)* from Tensorflow     
Check *[Gradam](https://arxiv.org/abs/1610.02391)*     
Check *[here](https://towardsdatascience.com/demystifying-convolutional-neural-networks-using-gradcam-554a85dd4e48)* from Towards Data Science     
Check *[here](http://gradcam.cloudcv.org/)* for more info
