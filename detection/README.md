# Fish Detection

YOLOv8 will be trained to automatically detect Picasso triggerfish (*Rhinecanthus aculeatus*) from videos. 

There are a series of Jupyter Notebooks that can be used to follow the steps.

## 1. Annotating a dataset [Link to notebook](detection/annotating_using_cvat.ipynb)
Here we use CVAT to annotate our dataset. For our wild fish, we have started with 10,102 images.

## 2. [Training a basic YOLOv8 Detector](YOLO_training.ipynb)
This notebook was designed for Mac users and uses cpu for training. 

## 3. YOLO Training Optimization
This notebook shows how to improve your trained model by augmenting the training dataset.

## 4. [Training a YOLOv8 Detector on Linux](YOLO_training_linux.ipynb)
This notebook was made for Linux users and uses gpu for training. It also includes code to:
* explore the accuracy of the trained model
* retrain another model for greater accuracy
* compare accuracy of the models
* plot error rates for different size categories of bounding boxes
* plot a histogram of confidence scores for True Positives and False Positives
