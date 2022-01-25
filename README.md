# Dataset Condensation
The number of data to train deep learning model is getting bigger and bigger, for example the data used for benchmarking machine learning model before 2000 is toy dataset like MNIST and it continue to became bigger like cifar-10/cifar-100 and now one of the biggest dataset is Imagenet with a million of image and thousand of label. there is a imagenet version that is used for more than 20000 class classification with more than 14 million data. this number of data to train deep learning model just keep increasing. The ammount of memory to store this data is really big.

As the number of data increase,the model is just getting bigger too,this make the training time of the model became longer,even when using a lot of computation.

Dataset Distillation is a method to reduce the size of the dataset to train deep learning model with as little as possible performance drop from the original dataset.  

In this notebook I will try to implement on of the algorithm to achieve this using (<a href = "https://arxiv.org/abs/2006.05929">Dataset Condensation with Gradient Matching</a> 
) and try to distill the image in the MNIST dataset.

# Acknowledgments
This This notebook is my implementaion of <a href = "https://arxiv.org/abs/2006.05929">Dataset Condensation with Gradient Matching</a> 
All credit goes to the authors of <a href = "https://arxiv.org/abs/2006.05929">Dataset Condensation with Gradient Matching</a> , Bo Zhao, Konda Reddy Mopuri, Hakan Bilen
