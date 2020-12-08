# COVID-GANs
Covid-19 Diagnostic Data Augmentation using Generative Deep Learning models to automate detection of Covid-19 

# Abstract:
COVID-19 had become the new norm since the pandemic. While the number ofcases are rising on a daily basis, there is a steady need to keep up rising number of cases and automate the diagnosis of COVID-19, off loading some of the work off the front-line workers. It is a known fact that medical image data suffers from skewness due to the limited availability of positive COVID-19 patient data. Deeplearning models rely heavily on the uniformity of the data to produce a good result and hence often overfit on highly skewed data.  Increasing the number oftraining samples has been shown to provide better classification accuracy and more generalizabilty. Due to strict protocols for medical data collection, it is not feasible to collect additional data for training.  In a scenario like this, the best approach is to perform data augmentation on the available training samples to reduce class imbalance and generate more samples.  Many approaches to data augmentation have been proposed, from basic image transformations to using a Generative network to create new images. In this work, we apply a combination of Variational Autoencoders and Generative Adversarial Networks to augment theCOVID-19 data on which a CNN-based classifier is trained to achieve a better performance.

# Classifier Model Evaluation:

Classifier Models | Vannila ResNet18 | Vannila ResNet34  | Modified ResNet18  | Inverted BottleNeck ResNet  | VGG-16 
--- | --- | --- | --- |--- |--- |
Accuracies | 77.78% | 88.89% | 74.07%| 74.00% | 75.00% 
