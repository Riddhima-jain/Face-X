## Overview
Face Recognition Using opencv, keras and tensorflow.

This model uses VGG-19 model for the recognition of the  User face.

Program is trained for 5 epochs, You can increase the number of epochs and the number of layers accordingly.

## ScreenShots

<img src="Screenshot from 2020-12-11 21-34-18.png" height="250px">
<img src="Screenshot from 2020-12-11 17-59-00.png" height="250px">

### Dependencies:
* pip install numpy
* pip install pandas
* pip install tensorflow
* pip install keras
* pip install opencv-python

Download haarcascades file from here=> https://github.com/opencv/opencv/blob/master/data/haarcascades/haarcascade_frontalface_default.xml


## Quick Start

- Fork and Clone the repository using-
```
git clone https://github.com/akshitagupta15june/Face-X.git
```
- Create virtual environment-
```
- `python -m venv env`
- `source env/bin/activate` (Linux)
- `env\Scripts\activate` (Windows)
```
- Install dependencies-

- Headover to Project Directory- 
```
cd Recognition using vgg-19
```
- Create dataset using -
```
- Run create_dataset.py on respective idle(VS Code, PyCharm, Jupiter Notebook, Colab)
```
Note: Do split the dataset into Train and Test folders.

- Train the model -
```
- Run train_model.py 
```
Note: Make sure all dependencies are installed properly.

- Final-output -
```
- Run displaying_output.py
```
Note: Make sure you have haarcascade_frontalface_default.xml file 


