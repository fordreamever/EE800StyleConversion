Image Style Conversion

Introduction

Super resolution convolutional neural network (SRCNN) is end-to-end mapping between LR images and corresponding HR images. 
SRCNN has experimentally verified that adjusting the number of network’s layer, 
the size of filter and the number of filters in each layer can have effect on reconstruction results.

I include train and test code in master branch.
The model 'vgg-verydeep-19' is also included in /data.
(Your GPU memory should >= 6GB)




How to train & test

1.You may compile matconvnet first by running gpu_compile.m  (you need to change some setting in it)

For more compile information, you can learn it from www.vlfeat.org/matconvnet/install/#compiling

2.Use test_vgg19.m to have fun~
