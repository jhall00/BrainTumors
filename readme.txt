Comp for Health and Medicine Final Project
Brain Tumor Classification
Classifies image as either glioma, meningioma, pituitary, no tumor

Github link: https://github.com/jhall00/BrainTumors

Download dataset from https://www.kaggle.com/datasets/sartajbhuvaji/brain-tumor-classification-mri

3 jupyter notebook files containing models (one for ResNet, one for DenseNet, one for LeNet)
1 jupyter notebook file containing evaluation metrics (for DenseNet)
1 jupyter notebook file containing thought process for a Multiscale CNN

In the notebooks we loaded the data in from a directory named "BrainTumorData". Within that folder there 
are two folders from the downloaded dataset, "Training" and "Testing". 



We have saved the models we used for DenseNet (The one with data aumentation is myModelDenseNet and the 
one without is myModelDenseNet2)

The ResNet model checkpoint saved as resNetModule.pt.zip
