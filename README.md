# Liscense Plate Detection using CNNs:
---

A project that detects and draws a bounding box over the Liscense Plate(s) detected in an image using 
1. DL approach with CNN
2. ML approach with HOG & SVM 
and to draw a contrast between the two

## Environment:

* Coded in Python 3.7
* This was trained in a cloud runtime with a GPU (Colab).

## Folder/File structure:

* **data** - contains the 'db' folder which contains 'images' and 'annotations' which serve as the DATASET for the model
* **ML_HOG_SVM__LiscensePlate.ipynb** - Code to train and visualise results for ML HOG and SVM.
* **DL_CNN__LiscensePlate.ipynb** - Code to train and visualise results for CNNs.
* **License Plate Detection Results Final.pdf** - pdf file containing a detailed report of our model.


## Instructions to run code:

* Run ```pip install matplotlib numpy tensorflow tqdm random keras cv2``` to install the required dependencies.
* Set up necessary environment to execute/ view a .ipynb file either locally or in the cloud

## Running the code

1. Note that to run the code, the .ipynb files and the 'db' folder should be in the SAME Directory
