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
- Modify the paths for the background image, labels.txt, and pneumonia_classifier.h5 file according to your system folder.
  
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




<img width="850" height="627" alt="Screenshot 2025-08-23 at 8 37 21 PM" src="https://github.com/user-attachments/assets/713b54fb-5185-4fdc-9c76-9c9bc2f349cc" />

<img width="850" height="627" alt="Screenshot 2025-08-23 at 8 39 05 PM" src="https://github.com/user-attachments/assets/b7581444-0ea1-4576-ae4b-3c1f3d89c0cf" />

