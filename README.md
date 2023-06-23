# Image Classification for Historical Documents: A Study on Chinese Local Gazetteers
## Overview
We present a novel approach for automatically classifying illustrations from historical Chinese
local gazetteers using modern deep learning techniques. Our goal is to facilitate the digital organiza-
tion and study of a large quantity of digitized local gazetteers. We evaluate the performance of eight
state-of-the-art deep neural networks on a dataset of 4,309 manually labeled and organized images
of Chinese local gazetteer illustrations, grouped into three coarse categories and nine fine classes
according to their contents. Our experiments show that DaViT achieved the highest classification
accuracy of 93.9% and F1-score of 90.6%.
This repository provides an example code for training deep learning models to classify illustrations from historical Chinese
local gazetteers.
## Dataset
We apply several data preprocessing techniques to our dataset, including image binarization, resizing, border cropping, and data augmentation.

[Train set Image](<https://drive.google.com/uc?export=download&id=1a1Yu9hHvHq4x3SluiyREpJW4Rr0SWl_N>)

[Train set Label (nine-class dataset)](<https://drive.google.com/uc?export=download&id=1D2QCOSbUH8ZX8OYhnZw08jatxVja0EVi>)

[Train set Label (three-category dataset)](<https://drive.google.com/uc?export=download&id=1cJ_yZxj4wVyBUGSouwiN1RUZwPeW2zNf>)

[Test set Image](<https://drive.google.com/uc?export=download&id=11gC_Why2OHo-_ObhaxyOwKXiPpoXTnwL>)

[Test set Label (nine-class dataset)](<https://drive.google.com/uc?export=download&id=1avLOcZEtptZtIu1W0dWQRX9meOdnAkDl>)

[Test set Label (three-category dataset)](<https://drive.google.com/uc?export=download&id=1Dy7IcPAjb5Dj16kR5o4D02wYZGNrSxZY>)
