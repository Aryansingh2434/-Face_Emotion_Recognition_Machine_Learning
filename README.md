# 📖 Description
A machine learning-based system that detects and classifies human facial emotions 
(e.g., Happy, Sad, Angry, Neutral, Surprise) from real-time or static images using computer vision and deep learning models.

Features 
- Real-time face detection using OpenCV
- Emotion classification using CNN-based model
- Pre-trained model support (FER2013, custom trained)
- Webcam or image input support
- Emotion heatmaps (optional)


Tech Stack  used 
- Python
- OpenCV
- TensorFlow / PyTorch
- Keras
- NumPy
- Matplotlib
- FER2013 dataset

Model  overview
- CNN architecture with 4 convolutional layers and dense layers
- Trained on FER2013 dataset (35,000+ grayscale facial images)
- Output: one of ['Angry', 'Disgust', 'Fear', 'Happy', 'Sad', 'Surprise', 'Neutral']
