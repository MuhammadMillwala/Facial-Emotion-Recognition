# Facial Emotion Recognition

This repository contains code for running facial emotion detection on 'icml_face_data' dataset from kaggle using the `facial_emotion_detection.ipynb` file and generating data (faces of size 48x48x3) using the `dateGeneration` file.

## Getting Started

### Prerequisites

To run the `facial_emotion_detection.ipynb` file, you will need to have the following installed:

- Python 3
- Jupyter Notebook
- OpenCV (cv2)
- Keras
- TensorFlow

This is a Python script that uses the MTCNN library to detect faces in images. The script takes an input image file and outputs a new image file with the faces detected and bounded by rectangles.

## Usage

To run the facial_emotion_detection script, you will need to have Python 3 and the Keras library installed. You can install Keras using pip:

```
pip install keras
pip install keras
```

To run the dateGeneration script, you will need to have Python 3 and the MTCNN library installed. You can install MTCNN using pip:

```
pip install mtcnn
```

Note: Make sure that the input image is preprocessed to match the input shape of the VGG16 model.


### Running the Code

1. Clone this repository to your local machine.
2. Run the `dateGeneration` file to generate synthetic date data.
3. Open `facial_emotion_detection.ipynb` in Jupyter Notebook.
4. Update the `DATASET_PATH` variable in the second cell of the notebook to point to the location of the generated data.
5. Run the remaining cells in the notebook to perform facial emotion detection on the generated data.

## Results:

![fer0](https://user-images.githubusercontent.com/88310782/229899733-208ac579-08e6-4c43-9aa3-6cbe0593153a.png)
 
The epoch’s history shows that accuracy gradually increases and achieves ~70% accuracy on both training and validation dataset. Also, ReduceLROnPlateau is called whenever the accuracy plateaus.
 
![fer1](https://user-images.githubusercontent.com/88310782/229899851-90396273-0909-4828-bfdb-0fc0a0ffa69c.png) 

Plotting the distribution of training and validation metrics:

![fer2](https://user-images.githubusercontent.com/88310782/229899862-71be6a07-5616-46a5-8d86-66391429825e.png)


## Acknowledgments

- This project was inspired by [(https://medium.com/analytics-vidhya/facial-emotion-recognition-fer-using-keras-763df7946a64 )] on facial emotion detection.
