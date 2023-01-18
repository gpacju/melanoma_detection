# Melanoma Detection
Melanoma Detection is a case study for detecting skin diseases based on captured skin images.

## Table of Contents
* [Objective](#objective)
* [Study Details](#study-details)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## Objective
- The main objective of this study is to build a CNN model capable of predicting skin diseases based on given images.

## Study Details
- Build a CNN model capable of detecting skin diseases based on provided images.
- The goal is to perform the following activities using the historical data
  - **Data Understanding**: Define train and test paths and read the data.
  - **Dataset creation**: Create train & validation dataset from the train directory 
  - **Dataset visualisation**:  Visualize one instance of each classes presen in the dataset 
  - **Model Building & Training**: Create a first CNN model, which can accurately detect all classes present in the dataset.
  - **Data augmentation**:Chose an appropriate data augmentation strategy to resolve underfitting/overfitting 
  - **Model Building & Training**: Create a second CNN model after data augumentation.
  - **Handling Class imbalance**: Handle class imbalance by creating augumented images for each class.
  - **Model Building & Training**: Create a third CNN model after handling class imbalance.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- The initial CNN model was overfitting. A huge gap observed between train and validation accuracies after 20 epochs.
- The second CNN model reduced overfitting. However, it's training accuracy was around 65% only after 20 epochs. 
- The third CNN model increased training and validation accuracies and eliminating underfitting by extracting more features from resulted augumented image samples.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- numpy 
- pandas 
- matplotlib
- tensorflow
- keras
- PIL
- Augumentor

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
- This project is my first one on artificial neural networks. I'd like to thank my mentors: **Shambhu Kumar** and  **Siddesh Gunjal**.

## Contact
Created by [@gpacju] - feel free to contact me!

