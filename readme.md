# A DEEP LEARNING-BASED SYSTEM FOR DETECTING SYNTHETIC IMAGES AND VIDEOS

## 🔍 Overview  
A full-stack deepfake detection system using a 10-layer CNN model. The application identifies manipulated images and videos in real time, combining deep learning with an interactive web interface.

## 🚀 Features  
- CNN-based binary classification for deepfake detection  
- Real-time frame-by-frame analysis  
- >99% training and validation accuracy  
- FastAPI backend and React.js frontend  
- Tailwind CSS for a clean, responsive UI  
- Visual evaluation metrics: ROC-AUC, Confusion Matrix, Precision, Recall

## 🧠 Model Highlights  
- Input: 224x224x3  
- 653K+ trainable parameters  
- Early layers: 64 filters, kernel size 5  
- Final layers: dilated convolutions + dropout (0.5)  
- Sigmoid activation for output classification

## 🛠️ Tech Stack  
- **Frontend**: React.js, Tailwind CSS  
- **Backend**: FastAPI  
- **Model**: TensorFlow, Keras  
- **Image Processing**: OpenCV  
- **Languages**: Python 3.10+, JavaScript (Node.js 18.19+)
