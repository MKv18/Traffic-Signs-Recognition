# Traffic Sign Recognition

This project is a traffic sign recognition system that can identify and classify traffic signs from images. The system uses machine learning algorithms to detect and recognize traffic signs, and it can be used in various applications such as autonomous vehicles and advanced driver assistance systems (ADAS) in future.

## About the project

This project is a real-time traffic sign recognition system built using Python, OpenCV, and a pre-trained CNN model, capable of detecting and recognizing traffic signs from both video streams and images.

The project includes a Jupyter notebook with the following:

1. Data exploration and preprocessing
2. Model training and evaluation
3. Model deployment

## Data Sources
https://www.kaggle.com/datasets/meowmeowmeowmeowmeow/gtsrb-german-traffic-sign/data 

##Dataset
The dataset used in this project is the German Traffic Sign Dataset. This dataset contains more than 50,000 images of traffic signs belonging to 43 different classes. The images are in color and have a resolution of 32x32 pixels. The dataset is divided into training, validation, and testing sets, with 39,209, 12,630, and 12,630 images, respectively.

The dataset is stored in the data directory of the Git repository. The data directory contains three subdirectories: training, validation, and testing. Each subdirectory contains the images for the corresponding dataset.

##Code
The code for this project is written in Python and is located in the FinalCode directory of the Git repository. The code is a Jupyter notebook that contains the following sections:

**Data Loading:** This section loads the dataset from the data directory and preprocesses it for training and testing. The section uses the tensorflow library to load the images and their corresponding labels.
**Data Augmentation:** This section applies data augmentation techniques to the training dataset to increase its size and diversity. The section uses the tensorflow library to apply random rotations, translations, and zooms to the images.
**Model Architecture:** This section defines the neural network architecture used for traffic sign recognition. The architecture is based on the VGG16 model, which is a convolutional neural network (CNN) architecture that was proposed in 2014. The section uses the tensorflow and keras libraries to define and train the model.
**Training:** This section trains the neural network model using the training dataset. The section uses the tensorflow library to train the model and save the trained model to a file.
**Testing:** This section tests the neural network model using the testing dataset. The section loads the trained model from a file and uses it to classify the images in the testing dataset. The section uses the tensorflow library to load the model and classify the images.
**Evaluation:** This section evaluates the performance of the neural network model using various metrics, such as accuracy, precision, recall, and F1 score. The section also plots the confusion matrix to visualize the model's performance.
**Prediction:** This section uses the trained model to predict the class of a given traffic sign image.

## Getting Started
To get started with the traffic sign recognition system, follow these steps:
## Technologies Used
- [Scikit learn](http://scikit-learn.org/stable)
- [Pandas](http://pandas.pydata.org/)
- [Numpy](http://www.numpy.org/)
- [Matplotlib](http://matplotlib.org/)
- [Seaborn](http://seaborn.pydata.org/)
- [Scipy](https://www.scipy.org/)
  
## Model
The machine learning model used for this project is a Custom LSTM. The model is trained on the training set and evaluated on the testing set.

## Results
The model achieved an accuracy of 62% on the testing set.

## Usage

This projectvcan be used in various applications such as autonomous vehicles and advanced driver assistance systems (ADAS)

## Roadmap
The traffic sign recognition system requires the following packages
-  Python 3.x
-  OpenCV
-  TensorFlow
-  Keras
-  Numpy

## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## Authors

########################################

In order to run the code make sure you pre-install all the dependencies such as LIME, Flask etc.

