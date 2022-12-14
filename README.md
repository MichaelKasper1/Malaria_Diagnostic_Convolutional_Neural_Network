# Malaria_Diagnostic_Convolutional_Neural_Network

Skills: Deep learning, computer vision

Find the data for this project in this link: https://drive.google.com/file/d/1n3o1Xghpy9ufZwHkQFE5l5d9sUHQOUWM/view

In 2019, there were over 229 million cases of malaria with over 400,000 deaths. 67% of these deaths were children under the age of 5. The traditional gold standard of malaria requires and experienced technician. Using deep learning, we can provide more accurate diagnosis of malaria without the need for experienced technician to read the results. Ultimately, implementation of this project in the world of public health would help reduce transmission and provide diagnostic information to save lives.

This repository includes Exploratory Data Analysis, Data Preprocessing, and 4 Convolutional Neural Networks that Diagnose Malaria from Images of Red Blood Cells at a 98% Accuracy.

The first file is Exploratory Data Analysis. In this file, I load and explore the data. The data is cropped images of red blood cells. These cells are prelabeled for this project as 0 representing and uninfected red blood cell or 1 representing a parasitized cell. First, Exploratory Data Analysis is performed examining the data set. This data admitedly is quite clean and balanced. Color of pixels was changed using OpenCV. Gaussian blurring was considered but not used.

The next file creates 4 CNNs with different architecture. Some of them use batch normalization, transfer learning, and different numbers of max pooling layers. Ultimately, one of the relatively simple models was chosen to and tested for an accuracy of 98% giving correct diagnoses.

This is a lot higher than the average rate of accuracy worldwide for technicians which I have read to be around 93%.
