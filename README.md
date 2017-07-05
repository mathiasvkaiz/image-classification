# image-classification

## Deep Learning Foundation Nanodegree - Project 2
In this project, you'll classify images from the [CIFAR-10 dataset](https://www.cs.toronto.edu/~kriz/cifar.html). The dataset consists of airplanes, dogs, cats, and other objects. The dataset will need to be preprocessed, then train a convolutional neural network on all the samples. You'll normalize the images, one-hot encode the labels, build a convolutional layer, max pool layer, and fully connected layer. At then end, you'll see their predictions on the sample images.

### Install
This project uses the following software and Python libraries:

- Python 3.5
- pandas 
- matplotlib 
- scipy scikit-learn

You will also need to have software installed to run and execute a [Jupyter Notebook](http://ipython.org/notebook.html).

To install tensorflow use command:
```pip install tensorflow```

To install all other dependency packages use command:  
```pip install -r floyd_requirements.txt```


### Code
This project contains 4 files:

- dlnd_image_classification.ipynb:  
This is the main file where you will answer questions and provide an analysis for your work. 
- floyd_requirements.txt:  
Pip manager package dependency file
- pronlem_unittests.py:  
Unit test file
- helper.py:  
Helper code. Do not modify.
  
### Run
In the Terminal or Command Prompt, navigate to the folder containing the project files, and then use the command:  
```jupyter notebook dlnd_image_classification.ipynb```
