# sign-language-digits



## Goals and motivations

This repository is created to showcase some basic workflow for computer vision classification tasks using relatively straightforward Sign Language Digit dataset. As a side goal, I wanted to present the project in a way that might be helpful to others having initial problems figuring out the workflow on their own. What is more, it acts as an easily expandable blueprint for more complex projects requiring some additional steps



## Dataset

The full dataset in it's unchanged form can be found [here](https://www.kaggle.com/ardamavi/sign-language-digits-dataset/). Be aware that it has some mismatched labels, while the one used by me doesn't. This dataset contains 2062 pictures of both women and men showing sign language digits, ranging from 0 to 9. The dimensions for each image are 64 by 64 pixels. Each of the 10 classes are evenly distributed within the dataset. Be aware, that the images come as normalised NumPy arrays and labels are one-hot encoded.



## Project structure

The project is stored in the [cnn-digit-classifier](https://github.com/wozniakmikolaj/sign-language-digits/blob/master/cnn-digit-classifier.ipynb) notebook for better readability. The dataset can be found in the [data](https://github.com/wozniakmikolaj/sign-language-digits/tree/master/data) folder. Requirements.txt contains libraries necessary to run the project.