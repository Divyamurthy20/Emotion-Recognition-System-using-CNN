# Emotion-Recognition-System-using-CNN
This project identifies human emotions from facial images using a Convolutional Neural Network (CNN).   The system is trained on labeled facial expressions and predicts emotions such as Happy, Sad, Angry, Neutral, Fear, Surprise, and Disgust.

##  Features
- CNN model trained entirely on Kaggle
- Dataset sourced from Kaggle (facial emotion images)
- Preprocessing pipeline for grayscale conversion, resizing, and normalization
- High-accuracy emotion classification across multiple categories
- Notebook-friendly, reproducible workflow
- Real-time prediction script (optional)

##  Dataset
- Source: https://www.kaggle.com/datasets/jonathanoheix/face-expression-recognition-dataset
- Includes emotions like *Happy, Sad, Angry, Neutral, Fear, Surprise,* and *Disgust*


##  Model Architecture
- Convolutional layers  
- MaxPooling layers  
- Dropout regularization  
- Dense layers  
- Softmax classifier  

##  Tech Stack
- Python  
- TensorFlow, Keras  
- OpenCV  
- Kaggle GPU (T4)  
- NumPy, Pandas, Matplotlib  

##  Workflow (Kaggle Notebook)
1. Import dataset from Kaggle  
2. Preprocess and augment images  
3. Build CNN architecture  
4. Train on GPU-enabled Kaggle environment  
5. Evaluate accuracy, loss, and confusion matrix  
6. Export model (.h5) for real-time inference  

 
