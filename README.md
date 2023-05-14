# Facial Emotion Recognition

This repository contains code for generating data using the `dategenerator` file and then running facial emotion detection on that data using the `facial_emotion_detection.ipynb` file.

## Getting Started

### Prerequisites

To run the `facial_emotion_detection.ipynb` file, you will need to have the following software installed:

- Python 3
- Jupyter Notebook
- OpenCV (cv2)
- Keras
- TensorFlow

This is a Python script that uses the MTCNN library to detect faces in images. The script takes an input image file and outputs a new image file with the faces detected and bounded by rectangles.

## Usage

To use this script, you will need to have Python 3 and the MTCNN library installed. You can install MTCNN using pip:

```
pip install mtcnn
```

To use this script, you will need to have Python 3 and the Keras library installed. You can install Keras using pip:

```
pip install keras
```

Note: Make sure that the input image is preprocessed to match the input shape of the VGG16 model.


### Running the Code

1. Clone this repository to your local machine.
2. Run the `dategenerator` file to generate synthetic date data.
3. Open `facial_emotion_detection.ipynb` in Jupyter Notebook.
4. Update the `DATASET_PATH` variable in the second cell of the notebook to point to the location of the generated data.
5. Run the remaining cells in the notebook to perform facial emotion detection on the generated data.

## Acknowledgments

- This project was inspired by [(https://medium.com/analytics-vidhya/facial-emotion-recognition-fer-using-keras-763df7946a64 )] on facial emotion detection.
