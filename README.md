# EMONET - Real-time Emotion Detector using CNN and Keras 🎥😃😡😱

## Project Description
EMONET is a real-time emotion detection system that utilizes Convolutional Neural Networks (CNNs) built with Keras to recognize six basic emotions - Angry, Fear, Happy, Neutral, Sad, and Surprise - from live video feeds. This project demonstrates the power of deep learning in facial emotion recognition with real-time integration.

## Table of Contents
- [Project Description](#project-description)
- [Technologies Used](#technologies-used)
- [Requirements](#requirements)
- [Usage Instructions](#usage-instructions)
- [Documentation](#documentation)
- [Project Roadmap](#project-roadmap)
- [Conclusion](#conclusion)

## Technologies Used
- 🐍 Python 3.x
- 🔗 Keras (with TensorFlow backend)
- 🎥 OpenCV
- 🔢 NumPy
- 📚 Public facial expression datasets
- 📓 Jupyter Notebook (for development)

## Requirements
- 🐍 Python 3.x
- 🔗 Keras
- TensorFlow
- 🎥 OpenCV
- 🔢 NumPy
- 📓 Jupyter Notebook
- 💻 Webcam (for real-time video feed)

### Installation
1. Clone this repository:
    ```bash
    git clone https://github.com/Dtechking/NM_Emotion_Detection_AI
    ```

## Usage Instructions
1. **Run Jupyter Notebook:**
    Open the `Emotion_Detector.ipynb` file in Jupyter Notebook:
    ```bash
    jupyter notebook Emotion_Detector.ipynb
    ```

2. **Train the model:**  
   The notebook includes code for training the CNN model on emotion-labeled datasets. Ensure the dataset is properly set up and execute the relevant cells to train the model.

3. **Real-time emotion detection:**  
   After training, run the real-time emotion detection code using OpenCV for live video capture. A webcam will be required for this step.

4. **Face detection and emotion inference:**  
   The system uses Haar cascades to detect faces and inputs the detected faces into the trained CNN model for real-time emotion classification.

## Documentation
### Key Modules:
1. **Data Collection & Preprocessing:**  
   Utilizes public datasets for emotion detection, processes images by resizing, grayscale conversion, and splitting into training/validation sets.

2. **Model Architecture:**  
   Implements a CNN model using Keras with layers for feature extraction and emotion classification.

3. **Model Training:**  
   Trains the CNN with early stopping and model checkpointing to prevent overfitting.

4. **Real-time Integration:**  
   Uses OpenCV for live video capture, Haar cascades for face detection, and CNN for emotion inference in real-time.

### Metrics:
- Accuracy
- Loss

[Read more on the documentation](https://github.com/Dtechking/NM_Emotion_Detection_AI/blob/master/Docs/Darshan%20NM%20Sem6%20Report.pdf) 📄

## Project Roadmap
1. **Phase 1:** Model design, data collection, and training.
2. **Phase 2:** Integrate face detection and live video processing with OpenCV.
3. **Phase 3:** Real-time emotion inference and testing.
4. **Phase 4 (Future Enhancements):** 
   - Improve model accuracy for different lighting conditions and facial poses.
   - Extend emotion classification to additional emotions.
   - Build a GUI for a user-friendly interface.

## Conclusion 🎯
The EMONET project successfully brings together deep learning and computer vision to provide real-time emotion recognition from live video feeds. With its robust CNN architecture, EMONET can recognize a wide array of emotions and adapt to different lighting conditions and facial expressions. This opens exciting possibilities for **human-computer interaction**, **emotion-aware systems**, and **sentiment analysis tools**. Future improvements will enhance its accuracy, and the integration of additional emotions and a graphical interface will make it even more versatile and user-friendly.

By utilizing cutting-edge techniques in **real-time video processing** and **deep learning**, EMONET takes a leap beyond static image analysis and delivers a system capable of **real-time interaction**, making it a highly promising tool for both personal and professional use cases. 🧠💡
