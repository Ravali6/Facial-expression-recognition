# Facial-expression-recognition
classifying images for expressions Dataset collected from keras
I.	INTRODUCTION
Face expressions convey social and emotional information between humans, and can say that they are the primary means of non-verbal communication finding its applications in surveillance, deceit detection etc. The recognition of those expressions has been an active research topic since the early nineties and there have been several advances in the past few years in terms of face detection and tracking, feature extraction mechanisms and the techniques used for expression classification. Most of the research on facial expression analysis is based on basic emotions: anger, fear, disgust, happiness, sadness, and surprise. This paper presents a Conventional Neural Network model approach along with a statistical model Support vector machine with the intention of finding a better possible way for the classification of basic facial emotions. 

II.	RELATED WORK
III.	DATA PREPROCESSING

IV.	CNN USING TENSOR FLOW
 SVM

 

Figure 1 : SVM model confusion matrix

Support Vector Machines classify data through determination of a set of support vectors, through minimization of the Structural Risk. SVMs provide a generic mechanism to fit the surface of the hyperplane to the data through the use of a kernel function. The SVM package used for experimentation is LIBSVM. LIBSVM features include parameterized kernel functions, different SVM formulations (variable optimization algorithms), and multi-class classification. 
 The data set was divided into ten subjects for training and one subject for testing. The dataset was adjusted for binary classification. The objective of this paper is to determine the highest possible accuracy attainable with SVMs classifying the Jaffee and Ck datasets, and compare its performance against recent CNN performance. The large number of features and well-defined classifications seemed to be a rich dataset for SVMs. 


V.	OTHER NEURAL NETWORKS
A.	Single Layer Perceptrons
Determining the overall performance of the SVM requires comparison against a proven technique, such as neural networks whereas a single layer neural network classified the Jaffee and Ck datasets with 86.266% accuracy. The time taken for training was 68.39 sec. The peak accuracy for SVMs is 98.98%.Time for training is comparable with 54.65 seconds, and for single layer perceptron it was 48 seconds. 
Using LVQ for classifying this dataset gave surprising results with an accuracy of 82%. 

