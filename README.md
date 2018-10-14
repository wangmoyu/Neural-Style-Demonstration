# Neural-Style-Demonstration
## Introduction
This is my post-graduate project in University College Cork.<br>
In this project, I fellow an article by [Gatys](https://arxiv.org/abs/1508.06576) to implement the neural style which is <br>
a method to achieve artist painting style transfer and also tried a domain transfer method to represent style.<br>
This project is based on Tensorflow with Python under Mac OS.<br>
If you are using Window Tensorflow to run this code directly, there could be a transcoding problem.<br>
The reference code of this project is based on [anishathalye](https://github.com/anishathalye/neural-style)<br>
All the involved techniques have been introduced in my project report.<br>
## Requirement 
This implement is based on a Convolution Neural Network.<br>
A [VGG-19](http://www.vlfeat.org/matconvnet/models/beta16/imagenet-vgg-verydeep-19.mat) network should be include in the file.<br>
## Related Work
If you are interested in neural style, here are some useful articles that could be helpful.<br>
[Neural Style Transfer: A Review](https://arxiv.org/abs/1705.04058v4)<br>
[Neural-Style-Transfer Papers and related work](https://github.com/ycjing/Neural-Style-Transfer-Papers)<br> 
## Results
Running  `python style_transfer.py --help`<br>
to view all the arguments.<br>
![](https://github.com/wangmoyu/Neural-Style-Demonstrateion/raw/master/interface-help.png)<br>  
Running  `python style_transfer.py --content content image path --styles style images path --output output path` <br>
to quickly start a style transfer process.<br>
![](https://github.com/wangmoyu/Neural-Style-Demonstrateion/raw/master/interface.png)<br>
A simple result:<br>
https://github.com/wangmoyu/Neural-Style-Demonstrateion/raw/master/pooling%20compare/content-image.jpg <br>
https://github.com/wangmoyu/Neural-Style-Demonstrateion/raw/master/pooling%20compare/style-image.jpg <br>
https://github.com/wangmoyu/Neural-Style-Demonstrateion/raw/master/pooling%20compare/result.jpg <br>
