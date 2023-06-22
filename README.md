# TAA 2023 Project 2 - Intel Image Scene Multiclass Classification

Inês Baptista (98384)

Ricardo Pinto (103078)

Github repository: https://github.com/zzzzz151/TAA-Project2

Download dataset (github doesn't accept more than 100MB): https://drive.google.com/file/d/1tYrowR_UF2wDQZjdrw32i90L7dzqy0Rf/view?usp=sharing

# Abstract

Over the past decade, image classification has emerged as a prominent research area, offering valuable insights for complex tasks like planetary exploration and unmanned driving. Among the various subproblems of image classification, scene image classification has gained significant attention. In this paper, we conduct a comprehensive review of the state-of-the-art techniques employed in this specific subproblem. Furthermore, we utilize the Intel Image Classification dataset, comprising diverse images of natural scenes worldwide, to construct and optimize four distinct Convolutional Neural Networks (CNNs). These CNN models are designed to accurately predict the type of scenery depicted in an image, such as sea, glacier, street, and more. By leveraging deep learning and fine-tuning strategies, we aim to achieve improved performance and enhance the applicability of scene image classification in real-world scenarios.

# Folder Structure 

This repository contains the code we implemented to complete the multiclass classification of the Intel Image Classification Dataset. The folder **models** contains the multiple fine-tuned models and their respective history. The notebook **analysis.ipynb** was used for analyzing the dataset. The file **cnn.ipynb** is the main notebook that was used to train the models.

# Test accuracies obtained by grid searching the 4 CNNs

**model_name=cnn1**

77.53% model_name=cnn1, batch_size=32, learning_rate=0.0001, model_file=models/cnn1_32_0.0001.h5

74.60% model_name=cnn1, batch_size=128, learning_rate=0.0001, model_file=models/cnn1_128_0.0001.h5

**78.63% model_name=cnn1, batch_size=32, learning_rate=0.001, model_file=models/cnn1_32_0.001.h5**

77.83% model_name=cnn1, batch_size=128, learning_rate=0.001, model_file=models/cnn1_128_0.001.h5

17.50% model_name=cnn1, batch_size=32, learning_rate=0.01, model_file=models/cnn1_32_0.01.h5

17.50% model_name=cnn1, batch_size=128, learning_rate=0.01, model_file=models/cnn1_128_0.01.h5

**model_name=cnn2**

84.10% model_name=cnn2, batch_size=32, learning_rate=0.0001, model_file=models/cnn2_32_0.0001.h5

79.27% model_name=cnn2, batch_size=128, learning_rate=0.0001, model_file=models/cnn2_128_0.0001.h5

**85.13% model_name=cnn2, batch_size=32, learning_rate=0.001, model_file=models/cnn2_32_0.001.h5**

84.87% model_name=cnn2, batch_size=128, learning_rate=0.001, model_file=models/cnn2_128_0.001.h5

17.50% model_name=cnn2, batch_size=32, learning_rate=0.01, model_file=models/cnn2_32_0.01.h5

68.93% model_name=cnn2, batch_size=128, learning_rate=0.01, model_file=models/cnn2_128_0.01.h5

**model_name=resnet**

47.60% model_name=resnet, batch_size=32, learning_rate=0.0001, model_file=models/resnet_32_0.0001.h5

41.20% model_name=resnet, batch_size=128, learning_rate=0.0001, model_file=models/resnet_128_0.0001.h5

56.97% model_name=resnet, batch_size=32, learning_rate=0.001, model_file=models/resnet_32_0.001.h5

52.17% model_name=resnet, batch_size=128, learning_rate=0.001, model_file=models/resnet_128_0.001.h5

60.00% model_name=resnet, batch_size=32, learning_rate=0.01, model_file=models/resnet_32_0.01.h5

**62.43% model_name=resnet, batch_size=128, learning_rate=0.01, model_file=models/resnet_128_0.01.h5**

**model_name=vgg16**

86.03% model_name=vgg16, batch_size=32, learning_rate=0.0001, model_file=models/vgg16_32_0.0001.h5

84.43% model_name=vgg16, batch_size=128, learning_rate=0.0001, model_file=models/vgg16_128_0.0001.h5

**87.77% model_name=vgg16, batch_size=32, learning_rate=0.001, model_file=models/vgg16_32_0.001.h5

87.17% model_name=vgg16, batch_size=128, learning_rate=0.001, model_file=models/vgg16_128_0.001.h5**

87.10% model_name=vgg16, batch_size=32, learning_rate=0.01, model_file=models/vgg16_32_0.01.h5

87.00% model_name=vgg16, batch_size=128, learning_rate=0.01, model_file=models/vgg16_128_0.01.h5


