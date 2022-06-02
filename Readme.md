# Face Attributes Recognition!

Deep learning revolves around identifying faces for various applications from logging into your phone with your face or searching through surveillance images for a particular suspect. In this project, deep learning models have been created to recognize expressions and attributes of celebrities  in the images by trying 3 different methods.
Part -1) Build own CNN model from scratch (In this Notebook)
Part -2) Apply data augmentation to generate new images and then build and analyze same model used in part-1
Part -3) Build a model using transfer learning with the help of State-of-art model (Mobilenet_V2)

## Required Libraries

The following libraries are required to be installed in the machine to run the python scripts. Python version of 3.7.13 with pip.
```bash
	pip3 install tensorflow matplotlib scikit-learn  pandas numpy keras seaborn
```

## Required Dataset format
All the models are build using images from the 'CelebFaces Attributes (celebA)' dataset . It is recommended to keep the image type as `'.jpeg' / '.jpg'` for better performance and convenience. Image size should be at least `'224*224'`.

Link to Dataset: https://www.kaggle.com/datasets/jessicali9530/celeba-dataset

## Supervised Learning Model (CNN)

> Make sure all required files are installed before running the command along with the dataset required 

```Notebook
Deep_learning_project_part1.ipnyb
```
## Data Agumentation using Tensorflow methods

> Make sure all required files are installed before running the command along with the dataset required 

```Notebook
Deep_learning_project_part2.ipnyb
```
## State-of-the-art  Models (Mobilenet_V2)

> Make sure all required files are installed before running the command along with the dataset required 

```Notebook
Deep_learning_project_part3.ipnyb
```
