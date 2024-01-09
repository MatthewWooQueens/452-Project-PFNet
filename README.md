# 452-Project-PFNet

All credit goes to the authors of [Camouflaged Object Segmentation With Distraction Mining](https://github.com/Mhaiyang/CVPR2021_PFNet).
This is a modified version of their code implemented in Google Colab. 

You'll need to have the 4 datasets uploaded to google drive. 
3 of the datasets can be downloaded from the papers website
Github for [NC4K](https://github.com/JingZhang617/COD-Rank-Localize-and-Segment) dataset.

The goal of this project was to attempt to make improvements to the papers original code. The improvements made included Enhanced Alignment Measure (E-Measure) for measuring the pixel accuracy of the models. Efficient Channel Attention Block which modifies the channel attention block to input feature maps into an average pooling layer and then a convulutional layer. Scaled Exponential Linear Unit which replaced the ReLU activation functions with SELU and a alpha dropout layer to allow self normalization of the network. Addition of gaussian white noise function to the joint transformation in order to generalize the model more. Lastly, the Dice coefficient loss function to replace the IOU loss function.
