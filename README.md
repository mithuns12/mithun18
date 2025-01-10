This repository hosts a Python-based face detection project that utilizes a pre-trained model from Google Teachable Machine. It provides a simple solution for detecting faces in both images and live video streams by leveraging machine learning techniques.

Key Features
Detects faces in images and real-time video feeds.
Integrates a pre-trained model from Google Teachable Machine.
Easy to implement and customize, making it perfect for beginners.
Prerequisites
To run the project, ensure you have the following:

Python 3.7 or higher
OpenCV library
NumPy library
A pre-trained face detection model from Google Teachable Machine
Installation Instructions
Set Up Google Teachable Machine:

Open Google Chrome and go to the Google Teachable Machine website. Click on Get Started.
Create a New Project:

In the New Project section, choose Image Model.
Choose the Standard Image Model:

Select the Standard Image Model option to start the model training process.
Upload and Train the Model:

Define the classes you want the model to recognize. You can upload images via webcam or Google Drive and train the model. The interface will show the comparison percentages between the classes.
Export the Model:

Once the training is complete, click Export the Model.
Download the Model Files:

In the TensorFlow tab, click on Download the Model to download a .zip file containing the model.
Set Up the Local Environment:

Open the provided Python code in a code editor like PyCharm or any other Python interpreter.
Extract and Place Model Files:

Extract the .zip file and copy the .h5 model file and the .txt file containing class labels. Place both files in your project directory.
Install Dependencies:

Open a terminal and install the required libraries for the project. Make sure you're using the correct Python version and TensorFlow version to avoid compatibility issues.
Run the Code:

After the libraries are installed, execute the script. The FaceFinder+ face detection model should now work and detect faces in both images and video streams.
