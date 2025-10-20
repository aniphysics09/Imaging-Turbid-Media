The Python codes in this repository contains the U-net based models trained for estimation of depth-map from microscopic images. The results of these models are published here:
https://doi.org/10.1117/12.3029573

The study shows that a surface with varying height profile, when covered with a turbid medium, imaged at different focal planes of a microscope. 
The multiple focal stacked images can be used as input of a trained model to predict the depth map.
For comparing the results, three different models were used with three different input shapes: 
256 x 256 x 10  # stack of 10 images as input
256 x 256 x 5  # stack of 5 images as input
256 x 256 x 1  # single image as input

The model gives an output of the shape:
256 x 256 x 1

The files 'Depth_from_ImageStack_10', 'Depth_from_ImageStack_5' and 'Depth_from_SingleImage' contains the model and its result for the three corresponding cases
