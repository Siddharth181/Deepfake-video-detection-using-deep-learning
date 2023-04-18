# Deepfake-video-detection-using-deep-learning
1.Introduction 


Deepfake videos are created by manipulating or replacing the original content with artificial content, which can be generated using artificial intelligence algorithms such as deep learning. The impact of deepfake videos is quite serious as it can create confusion, misinformation, and can even harm an individual's reputation. Therefore, it is essential to develop a mechanism that can detect deepfake videos.

This project aims to develop a deep learning-based approach for detecting deepfake videos. The proposed approach uses a pre-trained deep convolutional neural network (CNN) for extracting features from the video frames, and then a classifier is trained using these features to classify the video as real or fake.


2.Dataset


To train and evaluate the proposed approach, we need a dataset of real and fake videos. There are several datasets available online Deepfake Detection Challenge (DFDC).
These datasets contain videos that are either real or manipulated using different deepfake techniques.
The link for the dataset:https://www.kaggle.com/competitions/deepfake-detection-challenge/data

3. Structure


DeepFake Video detection :
This directory consists of the user interface code . Where a user can upload the video and submit it to the model for prediction. The trained model performs the prediction and the result is displayed on the screen.


Model Creation:
This directory consists of the step by step process of creating and training a deepfake detection model .

Documentations:
This Consists of the medium article and the poster for Deepfake video detection using deep learning. And also the Architecture diagram for the same.

4.Architecture Diagram


<img width="459" alt="image" src="https://user-images.githubusercontent.com/111408862/232812519-5a75d2cb-2b35-4f0f-a898-a05ac291d695.png">


5.Results


We evaluate the performance of the proposed approach on the DFDC dataset, which contains videos that are either real or manipulated using deepfake techniques. We use several performance metrics, such as accuracy, precision, recall,  and ROC curve, to evaluate the performance of the proposed approach.

6.Conclusion


In this project, we propose a deep learning-based approach for detecting deepfake videos. The proposed approach uses a pre-trained CNN for feature extraction and LSTM for classification. The experimental results show that the proposed approach achieves high accuracy in detecting deepfake videos.



7.Contributors

Siddhartha Talasila


Lavaneeth Reddy
