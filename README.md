# nofal82.github.io

# Food-11 Image Classification Project
## This project is about classifying images of food into 11 categories using deep learning and transfer learning techniques. The categories are:

•  Bread

•  Dairy product

•  Dessert

•  Egg

•  Fried food

•  Meat

•  Noodles/Pasta

•  Rice

•  Seafood

•  Soup

•  Vegetable/Fruit

The dataset used for this project is the Food-11 dataset, which contains 16,643 images of food from different sources. The dataset is divided into three subsets: training (9866 images), validation (3430 images), and evaluation (3347 images).

The model used for this project is a pre-trained ResNet-50 model with a custom classifier layer. The model is trained on the training subset and evaluated on the validation and evaluation subsets. The model achieves an accuracy of around 82% on the evaluation subset.

Requirements
To run this project, you need to have the following:

•  Python 3.6 or higher

•  TensorFlow 2.0 or higher

•  Keras 2.3 or higher

•  NumPy 1.18 or higher

•  Matplotlib 3.1 or higher

•  Scikit-learn 0.22 or higher

You also need to download the Food-11 dataset from this link: https://mmspg.epfl.ch/downloads/food-image-datasets/

Usage
To run this project, follow these steps:

1. 
Clone or download this repository to your local machine.
2. 
Extract the Food-11 dataset and place it in the same directory as the repository.
3. 
Open a terminal or command prompt and navigate to the repository directory.
4. 
Run the following command to train the model on the training subset and save it as food_model.h5:

python train.py

1. 
Run the following command to test the model on the validation and evaluation subsets and print the accuracy and confusion matrix:

python test.py

1. 
Run the following command to plot some sample images and their predictions:

python plot.py

License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgments
This project is based on the following resources:

•  https://www.kaggle.com/nofal82/food-11-usingtransferlearning

•  https://www.tensorflow.org/tutorials/images/transfer_learning

•  https://github.com/mtobeiyf/keras-flask-deploy-webapp
