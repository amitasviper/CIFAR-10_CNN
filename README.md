# CIFAR-10_CNN
[![N|Solid](https://secure.gravatar.com/avatar/7273c58dc017eec83667b50742ff6368?s=80)](https://www.linkedin.com/in/amitasviper/)

CIFAR-10 Convolutional Neural Network implementation using TensorFlow.


## Requirements
**Library** | **Version**
--- | ---
**Python** | **^3.6.5**
**Tensorflow** | **^1.8.0**
**Numpy** | **^1.14.3** 
**Matplotlib** | **^2.2.2** 

## Accuracy
This model is able to acheive 100% accuracy on training data and 96.08% accuracy on test data. The training data is composed of 40000 images and the test data consists of remaining 10000 images from the CIFAR-10 dataset.

This implementation contains 5 convulational layers having max-pooling and dropout in some of the layer. Apart from these, it has 3 fully connected layers at the end. All the covulational layers use ReLU as the activation function. The last fully connected layer uses Sigmoid as the activation fuction to get the final outputs as probability distribution among the 10 classes.

## Try this on your machine
### Clone this repository
```sh
git clone https://github.com/amitasviper/CIFAR-10_CNN.git
cd CIFAR-10_CNN
```

### Install the required dependencies
```sh
pip3 install numpy tensorflow matplotlib
```


### Train network
Run the `jupyter notebook` command in the project direcory to open the notebook. After this open the `ImageClassification` notebook in the browser and run all the cells.

Traning output:
```sh
Total batches are  312
 0 - [===>----------------------]  12% -Train Acc| [===>----------------------]  14% -Test Acc
 0 - [====>---------------------]  16% -Train Acc| [===>----------------------]  14% -Test Acc
 0 - [====>---------------------]  16% -Train Acc| [===>----------------------]  15% -Test Acc
 0 - [====>---------------------]  16% -Train Acc| [===>----------------------]  15% -Test Acc
 0 - [====>---------------------]  16% -Train Acc| [====>---------------------]  17% -Test Acc
 0 - [====>---------------------]  16% -Train Acc| [====>---------------------]  17% -Test Acc
 0 - [====>---------------------]  16% -Train Acc| [====>---------------------]  18% -Test Acc
 0 - [====>---------------------]  16% -Train Acc| [====>---------------------]  18% -Test Acc
 0 - [====>---------------------]  18% -Train Acc| [====>---------------------]  18% -Test Acc
 0 - [====>---------------------]  18% -Train Acc| [=====>--------------------]  22% -Test Acc
 0 - [=====>--------------------]  23% -Train Acc| [=====>--------------------]  22% -Test Acc
 0 - [======>-------------------]  27% -Train Acc| [=====>--------------------]  22% -Test Acc
 0 - [======>-------------------]  27% -Train Acc| [=====>--------------------]  23% -Test Acc
 0 - [======>-------------------]  27% -Train Acc| [======>-------------------]  27% -Test Acc
 0 - [=======>------------------]  30% -Train Acc| [=======>------------------]  30% -Test Acc
 0 - [=======>------------------]  30% -Train Acc| [========>-----------------]  32% -Test Acc
 0 - [=======>------------------]  30% -Train Acc| [========>-----------------]  33% -Test Acc
 0 - [========>-----------------]  34% -Train Acc| [========>-----------------]  33% -Test Acc
 0 - [========>-----------------]  34% -Train Acc| [=========>----------------]  36% -Test Acc
 0 - [==========>---------------]  41% -Train Acc| [=========>----------------]  36% -Test Acc
 0 - [===========>--------------]  45% -Train Acc| [=========>----------------]  36% -Test Acc
 0 - [===========>--------------]  45% -Train Acc| [=========>----------------]  37% -Test Acc
 0 - [===========>--------------]  45% -Train Acc| [=========>----------------]  38% -Test Acc
 0 - [===========>--------------]  45% -Train Acc| [=========>----------------]  38% -Test Acc
 0 - [===========>--------------]  45% -Train Acc| [=========>----------------]  39% -Test Acc
 0 - [===========>--------------]  45% -Train Acc| [==========>---------------]  41% -Test Acc
 0 - [===========>--------------]  45% -Train Acc| [===========>--------------]  44% -Test Acc
 1 - [============>-------------]  48% -Train Acc| [===========>--------------]  44% -Test Acc
 1 - [============>-------------]  48% -Train Acc| [===========>--------------]  46% -Test Acc
 1 - [============>-------------]  48% -Train Acc| [============>-------------]  48% -Test Acc
 1 - [============>-------------]  49% -Train Acc| [============>-------------]  48% -Test Acc
 1 - [============>-------------]  49% -Train Acc| [============>-------------]  49% -Test Acc
 1 - [=============>------------]  53% -Train Acc| [============>-------------]  49% -Test Acc
 1 - [=============>------------]  53% -Train Acc| [============>-------------]  50% -Test Acc
 1 - [=============>------------]  53% -Train Acc| [=============>------------]  54% -Test Acc
 1 - [=============>------------]  55% -Train Acc| [=============>------------]  54% -Test Acc
 2 - [==============>-----------]  57% -Train Acc| [=============>------------]  54% -Test Acc
 2 - [==============>-----------]  57% -Train Acc| [=============>------------]  55% -Test Acc
 2 - [==============>-----------]  59% -Train Acc| [=============>------------]  55% -Test Acc
 2 - [==============>-----------]  59% -Train Acc| [==============>-----------]  56% -Test Acc
 2 - [===============>----------]  61% -Train Acc| [==============>-----------]  56% -Test Acc
 2 - [===============>----------]  61% -Train Acc| [==============>-----------]  57% -Test Acc
 2 - [===============>----------]  61% -Train Acc| [==============>-----------]  57% -Test Acc
 3 - [===============>----------]  62% -Train Acc| [==============>-----------]  57% -Test Acc
 3 - [===============>----------]  62% -Train Acc| [==============>-----------]  58% -Test Acc
 3 - [===============>----------]  62% -Train Acc| [===============>----------]  61% -Test Acc
 3 - [===============>----------]  62% -Train Acc| [===============>----------]  61% -Test Acc
 3 - [===============>----------]  62% -Train Acc| [===============>----------]  61% -Test Acc
 3 - [===============>----------]  62% -Train Acc| [===============>----------]  62% -Test Acc
 3 - [===============>----------]  62% -Train Acc| [===============>----------]  63% -Test Acc
 3 - [================>---------]  64% -Train Acc| [===============>----------]  63% -Test Acc
 4 - [================>---------]  66% -Train Acc| [===============>----------]  63% -Test Acc
 4 - [================>---------]  67% -Train Acc| [===============>----------]  63% -Test Acc
 4 - [=================>--------]  68% -Train Acc| [===============>----------]  63% -Test Acc
 4 - [=================>--------]  68% -Train Acc| [================>---------]  64% -Test Acc
 5 - [=================>--------]  70% -Train Acc| [================>---------]  64% -Test Acc
 5 - [=================>--------]  70% -Train Acc| [================>---------]  65% -Test Acc
 5 - [=================>--------]  70% -Train Acc| [================>---------]  66% -Test Acc
 5 - [=================>--------]  70% -Train Acc| [================>---------]  66% -Test Acc
 5 - [=================>--------]  70% -Train Acc| [================>---------]  67% -Test Acc
 5 - [=================>--------]  70% -Train Acc| [================>---------]  67% -Test Acc
 5 - [=================>--------]  70% -Train Acc| [=================>--------]  68% -Test Acc
 5 - [==================>-------]  75% -Train Acc| [=================>--------]  68% -Test Acc
 6 - [==================>-------]  75% -Train Acc| [=================>--------]  69% -Test Acc
 6 - [==================>-------]  75% -Train Acc| [=================>--------]  69% -Test Acc
 7 - [==================>-------]  75% -Train Acc| [=================>--------]  71% -Test Acc
 7 - [==================>-------]  75% -Train Acc| [=================>--------]  71% -Test Acc
 7 - [==================>-------]  75% -Train Acc| [==================>-------]  72% -Test Acc
 7 - [===================>------]  76% -Train Acc| [==================>-------]  72% -Test Acc
 7 - [===================>------]  78% -Train Acc| [==================>-------]  72% -Test Acc
 8 - [===================>------]  78% -Train Acc| [==================>-------]  73% -Test Acc
 8 - [===================>------]  78% -Train Acc| [==================>-------]  73% -Test Acc
 8 - [===================>------]  78% -Train Acc| [==================>-------]  74% -Test Acc
 8 - [===================>------]  79% -Train Acc| [==================>-------]  74% -Test Acc
 9 - [===================>------]  79% -Train Acc| [==================>-------]  75% -Test Acc
 9 - [====================>-----]  80% -Train Acc| [==================>-------]  75% -Test Acc
 9 - [====================>-----]  80% -Train Acc| [===================>------]  76% -Test Acc
 9 - [====================>-----]  80% -Train Acc| [===================>------]  76% -Test Acc
 9 - [====================>-----]  80% -Train Acc| [===================>------]  77% -Test Acc
 9 - [====================>-----]  82% -Train Acc| [===================>------]  77% -Test Acc
10 - [====================>-----]  82% -Train Acc| [===================>------]  77% -Test Acc
10 - [====================>-----]  83% -Train Acc| [===================>------]  77% -Test Acc
10 - [=====================>----]  84% -Train Acc| [===================>------]  77% -Test Acc
10 - [=====================>----]  84% -Train Acc| [====================>-----]  80% -Test Acc
11 - [=====================>----]  84% -Train Acc| [====================>-----]  80% -Test Acc
11 - [=====================>----]  86% -Train Acc| [====================>-----]  80% -Test Acc
12 - [=====================>----]  87% -Train Acc| [====================>-----]  80% -Test Acc
12 - [=====================>----]  87% -Train Acc| [====================>-----]  82% -Test Acc
13 - [======================>---]  88% -Train Acc| [====================>-----]  82% -Test Acc
13 - [======================>---]  88% -Train Acc| [====================>-----]  83% -Test Acc
13 - [======================>---]  88% -Train Acc| [=====================>----]  84% -Test Acc
13 - [======================>---]  88% -Train Acc| [=====================>----]  84% -Test Acc
14 - [======================>---]  90% -Train Acc| [=====================>----]  84% -Test Acc
14 - [======================>---]  90% -Train Acc| [=====================>----]  86% -Test Acc
15 - [======================>---]  91% -Train Acc| [=====================>----]  86% -Test Acc
16 - [======================>---]  91% -Train Acc| [=====================>----]  86% -Test Acc
16 - [=======================>--]  92% -Train Acc| [=====================>----]  86% -Test Acc
16 - [=======================>--]  92% -Train Acc| [======================>---]  88% -Test Acc
16 - [=======================>--]  92% -Train Acc| [======================>---]  89% -Test Acc
17 - [=======================>--]  93% -Train Acc| [======================>---]  89% -Test Acc
18 - [=======================>--]  93% -Train Acc| [======================>---]  91% -Test Acc
18 - [=======================>--]  94% -Train Acc| [======================>---]  91% -Test Acc
19 - [=======================>--]  95% -Train Acc| [======================>---]  91% -Test Acc
20 - [=======================>--]  95% -Train Acc| [=======================>--]  92% -Test Acc
20 - [========================>-]  96% -Train Acc| [=======================>--]  92% -Test Acc
21 - [========================>-]  97% -Train Acc| [=======================>--]  92% -Test Acc
22 - [========================>-]  98% -Train Acc| [=======================>--]  92% -Test Acc
22 - [========================>-]  99% -Train Acc| [=======================>--]  92% -Test Acc
23 - [========================>-]  99% -Train Acc| [=======================>--]  93% -Test Acc
24 - [========================>-]  99% -Train Acc| [=======================>--]  94% -Test Acc
25 - [========================>-]  99% -Train Acc| [========================>-]  96% -Test Acc
26 - [=========================>] 100% -Train Acc| [========================>-]  96% -Test Acc
Training done in 21.205234 mins
###########################################################################################################
```


## Training statistics
Comparision of performance of CPU vs GPU during training the network.

**System** |**Device** | **Device Type** | **Batch size**  | **Time** | **Accuracy**
--- | --- | --- | --- | --- | ---
**Ubuntu 18.04** | **Nvidia GTX 960M** | **GPU** | **128** | **21m 12s** | **96.08 %**
**Mac OS Sierra** | **Intel i7-4770HQ** | **CPU** | **128** | **----** | **----**