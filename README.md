# Pneumonia-Classifier
Introduction
- This is a Streamlit application that classifies chest X-ray images as either pneumonia or not. The application uses a pre-trained TensorFlow model to make predictions.

Features
- Upload chest X-ray images in JPEG, JPG, or PNG format
- Classify images as either pneumonia or not
- Display classification results with confidence score
  
Prerequisites
To run this application, you need to have the following installed:
- Python 3.7 or later
- Streamlit (pip install streamlit)
- TensorFlow (pip install tensorflow)
- PIL (pip install pillow)
- NumPy (pip install numpy)
- Modify the paths for the background image, Label.txt, and pneumonia_classifier.h5 file according to your system folder.
  
Usage
- Upload a chest X-ray image using the file uploader.
- The application will display the uploaded image.
- The classification result, including the class name and confidence score, will be displayed below the image.

Technical Details
- The application uses the Streamlit library to build the user interface.
- The TensorFlow model is loaded from the model/pneumonia_classifier.h5 file.
- The classify function from the util module is used to make predictions on the uploaded image.
- The set_background function from the util module is used to set the background image.

Acknowledgments
- The pre-trained TensorFlow model is used for classification.
- The Streamlit library is used to build the user interface.
