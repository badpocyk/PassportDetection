# PassportDetection
<h2> In this motebook train neural network ResNet50, which determines the presence of a passport (or it could be something other document) on the photo </h2>

First part of notebook is augmentation. We have 2 folders which named "0" and "1" and include photos of people with and without document. 
And by augmentation we get 5 new photos from 1 old.

The next part is learning. We import pre-trained ResNet50, do some settings and learn this on GPU. 

The last part is pipeline for using our model. 
