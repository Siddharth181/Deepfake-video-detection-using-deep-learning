##Steps for pre-processing and model creation


- First the pre-processing is done


- Training of the model


- Precition of unseen data 

1.Dataset

The following dataset is used:https://www.kaggle.com/c/deepfake-detection-challenge/data

2. Pre-Processing of the data

- First Load the dataset


- Then spliting of the video into frames is done


- Now we are cropping the video hence reducing the frames so it can be easier to detect the fake or real video in the dataset


- After cropping the video it is saved to a new folder in the drive with the name Face_only_data


3. Training and Modelling

- First step is to load the preprocessed video and labels from a csv file.


- Create a pytorch model using transfer learning with CNN and LSTM.


- Now Split the data into train and test data


- Train the model


- Test the model


- Save the model in checkpoint.pt file


4.Predicting the model

- Load the saved pytorch model


- Predict the output based in trained weights.


5.Helpers

The codes in this file will
- Create csv file from glob
- Convert Json label file to csv label
- Copy files from one directory to another
- Remove Audio altered files from Deepfake Detection Challenge dataset
- Balancing dataset


6.Labels

- Contains Global_metadata.csv
