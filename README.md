# MistNet
MistNet is a convolution neural network for segmentation of rain and biology in weather radar data, developed by Tsung-Yu Lin et al. at University of Massachusetts Amherst

This repository contains a [PyTorch](https://pytorch.org/) implementation of MistNet.

For details, see our [publication](https://doi.org/10.1111/2041-210X.13280):

Tsung‐Yu Lin, Kevin Winner, Garrett Bernstein, Abhay Mittal, Adriaan M. Dokter, Kyle G. Horton, Cecilia Nilsson, Benjamin M. Van Doren, Andrew Farnsworth. Frank A. La Sorte, Subhransu Maji, Daniel Sheldon (2019) MistNet: Measuring historical bird migration in the US using archived weather radar data and convolutional neural networks, *Methods in Ecology and Evolution*, [DOI 10.1111/2041-210X.13280](https://doi.org/10.1111/2041-210X.13280)

To use MistNet in the [vol2bird](https://github.com/adokter/vol2bird) algorithm, a local copy of [`mistnet_nexrad.pt`](https://github.com/adokter/MistNet/blob/master/mistnet_nexrad.pt) is required in addition to the full installation of vol2bird, see vol2bird install instructions for details.
