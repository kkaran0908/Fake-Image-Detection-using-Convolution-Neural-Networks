# Fake-Image-Detection-using-Convolution-Neural-Networks
<h1> 1.Problem Statement</h1>
- Given an image we had to tell whether the image has been modified/altered or not.
<h2> 1.1 Dataset Description </h2>
<p>In our dataset there are two types of images 1. Fake images and 2. Pristine Images. Fake images are the images that have been altered, corresponding to each fake image we are having a mask. Mask is telling us which part of the image has been modified. Pristine images are the images that has not been modified. There are 450 fake images and 1050 pristine images in our dataset.</p>
<h2> 1.2 Sources/Useful Links</h2>
- Dataset : http://web.archive.org/web/20171013200331/http://ifc.recod.ic.unicamp.br/fc.website/index.py?sec=5
- Research Paper : https://ieeexplore.ieee.org/abstract/document/7823911
### Evaluation Metric
- Our dataset after preprocessing is balanced, and its a classification problem where given an image we have to predict whther the image is fake or pritine. So here we are using accuracy score as our evaluation metric.
<h1> Next Step:</h1>
Currently I am experimenting with the transfer learning to improve the accuracy of the model using pretrained architecture such as VGG16, VGG19, etc
