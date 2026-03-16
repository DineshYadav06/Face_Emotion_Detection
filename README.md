# 😊 Face Emotion Detection using Deep Learning

Face Emotion Detection is a computer vision and deep learning based project that detects and classifies human emotions from facial expressions in real-time. The system captures images from a webcam, detects faces using OpenCV Haar Cascade, and predicts emotions using a trained Convolutional Neural Network (CNN) model.

This project demonstrates how Artificial Intelligence and Deep Learning can be used to understand human emotions from facial expressions. Such systems can be used in human-computer interaction, mental health analysis, smart surveillance, and recommendation systems.

---

# 🎯 Objectives

The main objectives of this project are:

- Detect human faces from real-time webcam input  
- Analyze facial expressions using deep learning  
- Classify emotions into predefined categories  
- Demonstrate the use of CNN in image classification tasks  
- Build a real-time emotion recognition system using Python  

---

# 🧠 Emotions Detected

The model can detect the following emotions:

- Angry  
- Disgust  
- Fear  
- Happy  
- Neutral  
- Sad  
- Surprise  

---

# ⚙️ Technologies Used

- Python  
- OpenCV  
- NumPy  
- TensorFlow  
- Keras  
- Deep Learning (CNN)

---

# 🏗️ Project Workflow

1. Dataset Collection  
   Facial emotion datasets containing images of different expressions are collected and organized into folders.

2. Data Preprocessing  
   Images are resized to **48×48 grayscale format** and normalized for model training.

3. Model Training  
   A Convolutional Neural Network (CNN) model is trained using Keras.

4. Model Saving  
   The trained model architecture is saved as `.json` and weights as `.h5`.

5. Real-Time Detection  
   The webcam captures frames, detects faces, and predicts the emotion.

---

# 📂 Project Structure
Face_Emotion_Detection
│
├── images
│ ├── train
│ │ ├── angry
│ │ ├── disgust
│ │ ├── fear
│ │ ├── happy
│ │ ├── neutral
│ │ ├── sad
│ │ └── surprise
│ │
│ └── test
│ ├── angry
│ ├── disgust
│ ├── fear
│ ├── happy
│ ├── neutral
│ ├── sad
│ └── surprise
│
├── trainmodel.ipynb
├── realtimeDetection.py
├── emotiondetector.json
├── emotiondetector.h5
├── requirements.txt
└── README.md

---


---

# 🚀 Installation

Clone the repository
git clone https://github.com/your-username/Face_Emotion_Detection.git
Move to the project folder
cd Face_Emotion_Detection
Install required libraries
pip install -r requirements.txt


---

# ▶️ Run the Project
Run the following command:

python realtimedetection.py


The webcam will start and the system will detect faces and predict emotions in real time.

---

# 📊 Applications

Face Emotion Detection can be used in:

- Human Computer Interaction  
- Mental Health Monitoring  
- Smart Classroom Systems  
- Customer Feedback Analysis  
- Smart Surveillance Systems  
- Driver Emotion Monitoring  

---

# 🔮 Future Improvements

- Improve model accuracy using larger datasets  
- Deploy the model as a web application  
- Use advanced architectures like ResNet or MobileNet  
- Add real-time emotion statistics  
- Integrate voice and gesture recognition  

---

# 👨‍💻 Author

**Dinesh kumar Yadav**
If you like this project, consider giving it a ⭐ on GitHub

