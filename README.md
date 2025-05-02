<<<<<<< HEAD
 # 😷 Face Mask Detection API

This project uses a computer vision model to detect whether people are wearing face masks or not, and serves predictions via a FastAPI backend.

## 📂 Project Structure

face-mask-detection/
├── app/                      # FastAPI application
│   ├── main.py               # Entry point for the API
│   ├── model.py              # Model loading and prediction logic
│   ├── schemas.py            # Pydantic models for request/response
│   ├── utils.py              # Helper functions (optional)
│   └── __init__.py
│
├── models/                   # Directory to store trained model files
│   └── mask_detector.model   # Exported model file
│
├── notebooks/                # Jupyter notebooks for development
│   └── face-mask-detection.ipynb
│
├── train_export_model.py     # Script to train and export the model
├── .env                      # Environment variables like model path
├── requirements.txt          # Project dependencies
├── .gitignore                # Files and folders to ignore in git
└── README.md                 # Project documentation
=======
# 😷 Face Mask Detection API

This project implements a real-time face mask detection system using computer vision techniques with OpenCV and a pre-trained deep learning model. The application is served using a FastAPI backend, providing an efficient and lightweight API for mask detection in images or video streams.

## 🔍 Features

- Detects faces and classifies them as:
  - **With Mask**
  - **Without Mask**
- Real-time processing using OpenCV
- FastAPI backend with RESTful endpoints for image inference
- Supports image uploads via API

## 🧰 Tech Stack

- Python
- OpenCV
- TensorFlow/Keras or PyTorch (depending on your model)
- FastAPI
- Uvicorn

## 📂 Project Structure

>>>>>>> b3e85c067500c718586a6d8faa6e8c1ac744b2d3
