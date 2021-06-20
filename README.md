# UVSFE
Salient Feature Extractor for Adversarial Defense on Deep Neural Networks

| cuDNN | CUDA |
| :---- | :--- |
| 8.0   | 11.0 |

Requirements：
Python 3.6

Tensorflow-gpu -2.4 

keras2.3.1

Folder images are examples of benign images and their adversarial examples in MNIST. The former can be 
correctly classified while the latter may lead to misclassification. 
In model folder is well-trained CNN1 model with acc=99.79%.

Running the model

We can use the GAN.py script to train the model to gain SF and TF for adversarial defense and detetion
on MNIST. Advdetector is trained in detector.py 
Correct labels will be obtained when SF of adv is input to the model for classification. 


