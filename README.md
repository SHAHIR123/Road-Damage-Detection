# Road-Damage-Detection
Detect damages in the road from the images

## Use Case
**Create a model to detect the damaged road to use in real time computer vision application.**

> - Create a TensorFlow model which can detect damage roads and show defective road area in red boxes.

## Data Set
> - Used data set was a part of "roaddamagedataset" available on kaggle.

> - Training label was created manually for the used data set sample.

> - Image dataset can be found [here](https://www.kaggle.com/shahir/roaddamage)

> - Training label can be found [here](https://www.kaggle.com/shahir/training-label)

## Solution Model

> - Created TensorFlow model which can detect damage roads and**

> - show defective road area in red boxes
> - This model is inspired by yolo, specifically yolo v3.
> - YOLO model has been selected due to it's performance on real time and fatser object detection. We are going to use this model in real
time computer vision application. So compared R-CNN and SSD object detection model YOLO is the best fit for our purpose. YOLO use one-stage detector strategy that help to increase the speead of object detection.YOLO treat object detection as a regression problem, taking a given
input image and simultaneously learning bounding box coordinates and class labels.
> - initial YOLO model doing well in this object detection project for detetcting road damage.
> - Further training required with more data to achieve better accuracy.

## Architectural Choices
> - Jupyter Notebook
> - Pandas
> - Matplotlib
> - tensorflow
> - Keras
> - albumentations
> - PIL

## Data quality assessment & data pre -processing
> - Data quality assessment:
File Type – JPG and CSV File
Image data used in the model – 11 .jpg images
Label – CSV file manually created from the .xml annotation file
> - Data Pre-Processing:
Splitted image data set to train and valuation dataset.

## Model Performance Indicators
**Model Evaluation**
> - Final training loss: 0.25867342948913574
> - Final validation loss: 0.29891347885131836

Model has accuracy of around 75% in training data and around 71% in validation data.

## Further Work
> - Train model using more data set.
> - Hyper parameter tuing
> - Train with other object detection frame works.
