# faceapp
modified updated fork of my senior capstone project. realtime facial emotion ecognition with NN.
# Faceapp Analysis Tool demo

This project aims at recognizing facial emotions and head pose estimation in realtime via webcam. Multiple available datasets such as KDEF, RAF and FER2013 for emotion recognition were explored. emotion model uses Convolutional Neural Network with Dense Layer to determine the emotion of the person. It uses VGG 19 as the base model. dlib and opencv is used to detect faces. various researched pnp algorithms have been used to calculate headpose. GUI created with tkinter

# Setup

### Clone or download repo

If you have Anaconda setup with virtual environment, skip these 2 steps
### Install Anaconda Distribution with Python 3.7(https://www.anaconda.com/distribution/)
### Set up a Python Virtual Environment(https://www.learnopencv.com/install-opencv-3-and-dlib-on-windows-python-only/)
	follow steps 1-3.1


### Run 'python install.py' to check and install missing modules


### Install Tensorflow  
Note that this will require Python.
To install Tensorflow using pip, run the following in command prompt or Anaconda Prompt:  
```
pip install --upgrade tensorflow
``` 

To verify the install:  
```
python -c "import tensorflow as tf;"
``` 
### Download features
https://studentuncc-my.sharepoint.com/:u:/g/personal/syang48_uncc_edu/EUIVzXZ2oY9DkaYEJ-b62_sB8kMsadDJbzuxtKuF4qN1DQ?e=2DbwQj

### Download weights
https://studentuncc-my.sharepoint.com/:u:/g/personal/syang48_uncc_edu/EZZqLWaiSj5Erqo55MNS8sMBN7U1LwEMiMd2ig8l2IgG5w?e=qxoCgI

# Run

Open a powershell or cmd prompt window in root folder (open folder, shift+right click in the directory of folder and select 'Open powershell window here')


```
run `python init.py --output output`
```

# Train(WIP)

(WIP) use pretrained model

To train the model, run `python evalute.py`


# Acknowledgments
I use pretrained models and published algorithms in this project, please refer to the various sources for more information

http://www.academia.edu/6811887/A_Project_Report_On_FACIAL_EXPRESSION_RECOGNITION_USING_IMAGE_PROCESSING

https://becominghuman.ai/face-detection-with-opencv-and-deep-learning-from-video-part-2-592e2dee648

https://www.learnopencv.com/head-pose-estimation-using-opencv-and-dlib/

http://home.iitk.ac.in/~mangalam/CS771%20Course%20Project%20(%205th%20Semester,%20Fall%202016).pdf

https://github.com/topics/emotion-recognition?l=python&o=asc&s=updated

https://github.com/realpython/realpython-blog/blob/master/2014/2014-07-21-face-detection-in-python-using-a-webcam.markdown

http://www.paulvangent.com/2016/04/01/emotion-recognition-with-python-opencv-and-a-face-dataset/

http://www.consortium.ri.cmu.edu/ckagree/

http://www.pitt.edu/~emotion/ck-spread.htm

https://docs.opencv.org/3.4.3/d7/d8b/tutorial_py_face_detection.html

https://www.kaggle.com/c/challenges-in-representation-learning-facial-expression-recognition-challenge

https://docs.opencv.org/3.1.0/d4/d1b/tutorial_histogram_equalization.html

https://github.com/AsoStrife/Computer-Vision-Project#34-normalization-illumination
