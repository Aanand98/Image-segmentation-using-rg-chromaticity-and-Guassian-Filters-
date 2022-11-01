# Image-segmentation-using-rg-chromaticity-and-Guassian-Filters

# Installations

For libraries and their corresponding versions used in this code, please pip install requirements.txt using the following code:

pip install -r requirements.txt
For further details, please check the help option:
pip install --help

# Problem Description

This work is inspired by two different ideas of rg-chromaticity and image segmentation. The image segmentation is done using the gaussian distribution. RG-chromaticity has wide applications like extracting a particular object from an image, and it is shown to work efficiently. Given an image, although the rg-chromaticity aids significantly in segmentation, for a more efficient segmentation, gaussian distribution is used. This technique can be implemented on a single image, without any training. 

# Implementation

The original image is segmented into our object of interest, using rg-chromaticity and Gaussian distribution. The rg-chromaticity is used to find a patch from the image. Then masking and binary masking are performed on the original image to get only the desired segment of the entire image. From the patch obtained, Gaussian distribution is applied on the patch to find similar patches in the image, such that the similar patches create a segment.                                                                                                                                                                                                                                                                                     
