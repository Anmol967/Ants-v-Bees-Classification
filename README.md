# This repo contains the PyTorch implementation of ants vs bees binary image classification using Transfer Learning !

&emsp;● Various **image augmentations**(to reduce overfitting) like flips, rotations, cropping and color changes have been tried using **albumentations** library . 

&emsp;● Different classes have been created for different family of SOTA pre-trained models - **ConvNeXt**, **ResNeXt**, **ViT**, **EfficientNet**, **Xception** and **Inception** .

&emsp;● Other things like **autocasting** and **gradient scaling**(for faster computation and improved convergence), **learning rate decay** and **early stopping**(for tackling overfitting), **saving the best model** have been implemented .

&emsp;● Train, validation losses vs epochs have been visualized .

&emsp;● Best model - ConvNeXt with pre-trained weights frozen which gives **100%** accuracy on **validation** data .

&emsp;● Finally the best model is **loaded** and used for making **predictions** on test data .

Link to Kaggle dataset - https://www.kaggle.com/datasets/thedatasith/hymenoptera
