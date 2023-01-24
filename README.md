# COVID-19-Radiography-Using-ConvNets

## Abstract

The COVID-19 pandemic continues to have a negative impact on the fitness and well being of the worldwide population. A vital step in tackling the COVID-19 is a successful screening of patients, with one of the key screening approaches being radiological imaging using chest radiography. This study aims to automatically identify patients with COVID-19 pneumonia using digital x-ray images of the chest while increasing the accuracy of the diagnosis using Convolution Neural networks (CNN). The data-set consists of 5380 X-ray images consisting of 1345 X-ray images each of COVID patients, Lung Opacity, Normal patients and Viral Pneumonia. In this study, CNN based model have been proposed for the detection of coronavirus pneumonia infected patients using chest X-ray radiography and gives a classification accuracy of 93.77% (training accuracy of 99.81% and validation accuracy of 95.45%).

## Dataset

The Kaggle dataset was obtained by a team of researchers from Qatar University, Doha, Qatar, and the University of Dhaka, Bangladesh along with their collaborators from Pakistan and Malaysia in collaboration with medical doctors. The dataset consists of chest X-ray images for COVID-19 positive cases along with Normal and Viral Pneumonia images. 

The dataset contains 5380 radiography images divided into four categories: Covid-19, Lung Opacity, Normal, and Pneumonia. Each category contains 1345 images. For the evaluation, we split the images in a 6:2:2 ratio for the train/test/validation set per category.

Dataset Link: https://www.kaggle.com/datasets/tawsifurrahman/covid19-radiography-database

## Result Analysis

The performance of the model was evaluated using the training curve as plotted in Fig. 4. The accuracy after the 25 epochs for CNN, VGG-16 and VGG-19 model was found to be 84.75%, 89.77% and 93.77% respectively, as shown in below table , in which a value of 100% indicates a perfect accuracy. The loss, on the other hand, keeps on decreasing with each epoch and then it reaches critical point where it almost remains constant.

<p align="center">
  <img  src="https://user-images.githubusercontent.com/88145926/214232195-6dc10196-5d94-41da-80e5-1eafa7758347.png">
</p>

## Conclusion

We compared performances of CNN, VGG-16 and VGG-19 architectures using the Kaggle dataset. Performance metrics such as accuracy, F-score, precision, and confusion matrix
were used. We have demonstrated that with current limited and challenging COVID-19 datasets, our model could be used to develop suitable deep learning-based tools for COVID-19 detection. The model is capable of classifying Normal, COVID-19, Pneumonia and lung opacity conditions from X-Ray. Our study uncovers the challenging characteristics of the limited COVID-19 image datasets. This should be helpful for practitioners aiming to use these datasets for their research and development.
