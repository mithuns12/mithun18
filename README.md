

---

## FaceDetectAI: Python-Based Face Detection Using Google Teachable Machine

This repository hosts a Python-based face detection project called **FaceDetectAI**, which utilizes a pre-trained model from Google Teachable Machine. It provides a straightforward solution for detecting faces in both static images and live video streams using machine learning techniques.

### Key Features:
- Detect faces in both images and real-time video streams.
- Utilizes a pre-trained model from Google Teachable Machine.
- Easy to implement and customize, ideal for beginners.

### Prerequisites:
To run **FaceDetectAI**, you need the following:
- **Python 3.7 or higher** installed on your system.
- The **OpenCV** library for handling images and video streams.
- The **NumPy** library for numerical computations.
- A **pre-trained face detection model** from Google Teachable Machine.

---

### Step-by-Step Installation and Setup

#### Step 1: Set Up Google Teachable Machine

1. **Navigate to the Google Teachable Machine Website:**
   - Open **Google Chrome** or any browser and visit the [Google Teachable Machine website](https://teachablemachine.withgoogle.com/).
   - Click on **Get Started** to begin the model creation process.
   - ![image](https://github.com/user-attachments/assets/d740ea27-b4a0-4269-acc6-7d1573403333)


#### Step 2: Create a New Project

1. **Select Project Type:**
   - In the **New Project** section, choose **Image Model**.
![image](https://github.com/user-attachments/assets/df1d02f7-23d2-4458-b533-424e35b1ef9b)

#### Step 3: Choose the Standard Image Model

1. **Set Up the Model:**
   - Select the **Standard Image Model** option. This model type is suitable for classifying images into the categories you define.
   - ![image](https://github.com/user-attachments/assets/e9960d01-2172-4388-a6e0-b12c89898a59)


#### Step 4: Upload Images and Train the Model

1. **Define Classes:**
   - Create the classes you want the model to recognize. For example, create classes such as **"Face"** and **"No Face"**.
   
2. **Upload Images and Train:**
   - Upload images from your webcam or Google Drive. The model will learn to differentiate between the uploaded classes. You will be able to view the confidence percentages for each class.
![image](https://github.com/user-attachments/assets/4e0f3a6a-77f0-4b89-a8e7-5beb06a3b83b)

#### Step 5: Export the Model

1. **Export the Model:**
   - Once the model is trained, click **Export the Model** to prepare it for use in your project.

#### Step 6: Download the Model Files

1. **Download the Model:**
   - In the **TensorFlow** tab, click **Download the Model**. This will download a `.zip` file containing the model's files.

#### Step 7: Prepare Your Local Environment

1. **Set Up Your Python Environment:**
   - Open your Python code editor (e.g., **PyCharm**, **VSCode**) and copy the provided Python code.

2. **Extract and Place Model Files:**
   - Extract the `.zip` file and place the `.h5` model file and the `.txt` class labels file into your project directory.

#### Step 8: Install Required Libraries

1. **Install Dependencies:**
   - Open a terminal and install the necessary libraries by running:
     ```bash
     pip install opencv-python numpy tensorflow
     ```

2. **Ensure Correct Versions:**
   - Make sure you are using Python 3.7 or higher and that the installed TensorFlow version is compatible.

#### Step 9: Run the FaceDetectAI Code

1. **Execute the Script:**
   - After installing the dependencies, run the Python script. The **FaceDetectAI** system will now be able to detect faces in both images and real-time video streams.

---

### Additional Tips:
- **Customizing the Model:** You can further customize the model by adding more classes or improving the training data for more accurate face detection.
- **Compatibility Issues:** Double-check the Python and TensorFlow versions to ensure that everything works smoothly.
- **Enhancements:** Experiment with additional features such as emotion detection or tracking detected faces across video frames.

---

With **FaceDetectAI**, you can easily set up face detection in your project using a pre-trained model and enhance it as needed. Enjoy using the project and feel free to expand it further!

