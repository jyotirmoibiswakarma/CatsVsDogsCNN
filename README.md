# Dogs vs Cats Image Classification with Convolutional Neural Network
This repository contains Python code for a Convolutional Neural Network (CNN) model built using TensorFlow and Keras for the purpose of classifying images of dogs and cats. The model is trained on the "Dogs vs Cats" dataset obtained from Kaggle.

## Installation
## Clone the repository:
git clone https://github.com/jyotirmoibiswakarma/CatsVsDogsCNN.git

## Navigate to the project directory:
cd CatsVsDogsCNN

## Install the required dependencies:
from requirements.txt


## Obtain the Kaggle API token and place it in a file named kaggle.json in the root directory of the project.

## Download the "Dogs vs Cats" dataset from Kaggle using the following command:
!mkdir -p ~/.kaggle
!cp kaggle.json ~/.kaggle
!kaggle datasets download -d salader/dogs-vs-cats

## Unzip the downloaded dataset:
unzip dogs-vs-cats.zip

## Run the Python script to train the model and perform image classification:


## Model Architecture

The CNN model consists of the following layers:

Convolutional layers with ReLU activation
Batch normalization layers
Max pooling layers
Dropout layers for regularization
Dense layers with ReLU activation
Output layer with sigmoid activation

## Results
Training and validation accuracy and loss curves are plotted using Matplotlib.

## Example Usage
An example image (dog.jpg or cat.jpg) can be provided to the model for classification. The predicted class (dog or cat) will be displayed in the console.

## License
This project is licensed under the JBK License - see the LICENSE file for details.

## Acknowledgments
Kaggle for providing the "Dogs vs Cats" dataset

TensorFlow and Keras for deep learning framework
