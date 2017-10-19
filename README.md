
# Semantic Segmentation


### Build the Neural Network

##### Does the project load the pretrained vgg model?

passed tests.test_load_vgg(load_vgg, tf) 

##### Does the project learn the correct features from the images?

passed tests.test_layers(layers)

##### Does the project optimize the neural network?

passed tests.test_optimize(optimize)

##### Does the project train the neural network?

passed tests.test_train_nn(train_nn)

### Neural Network Training

##### Does the project train the model correctly?

On average, the model decreases loss over time. 

##### Does the project use reasonable hyperparameters?

The number of epoch equals 50 and batch size equals 2 (since any larger number result in out of memory error on the AWS GPU instance).

##### Does the project correctly label the road?

Inference result on three test images:

![Alt text](./runs/1508422290.994551/um_000054.png?raw=true "Optional Title")
![Alt text](./runs/1508422290.994551/umm_000026.png?raw=true "Optional Title")
![Alt text](./runs/1508422290.994551/uu_000044.png?raw=true "Optional Title")



---------------------------------

### Introduction
In this project, you'll label the pixels of a road in images using a Fully Convolutional Network (FCN).

### Setup
##### Frameworks and Packages
Make sure you have the following is installed:
 - [Python 3](https://www.python.org/)
 - [TensorFlow](https://www.tensorflow.org/)
 - [NumPy](http://www.numpy.org/)
 - [SciPy](https://www.scipy.org/)
##### Dataset
Download the [Kitti Road dataset](http://www.cvlibs.net/datasets/kitti/eval_road.php) from [here](http://www.cvlibs.net/download.php?file=data_road.zip).  Extract the dataset in the `data` folder.  This will create the folder `data_road` with all the training a test images.

### Start
##### Implement
Implement the code in the `main.py` module indicated by the "TODO" comments.
The comments indicated with "OPTIONAL" tag are not required to complete.
##### Run
Run the following command to run the project:
```
python main.py
```
**Note** If running this in Jupyter Notebook system messages, such as those regarding test status, may appear in the terminal rather than the notebook.

### Submission
1. Ensure you've passed all the unit tests.
2. Ensure you pass all points on [the rubric](https://review.udacity.com/#!/rubrics/989/view).
3. Submit the following in a zip file.
 - `helper.py`
 - `main.py`
 - `project_tests.py`
 - Newest inference images from `runs` folder  (**all images from the most recent run**)
 
 ## How to write a README
A well written README file can enhance your project and portfolio.  Develop your abilities to create professional README files by completing [this free course](https://www.udacity.com/course/writing-readmes--ud777).
