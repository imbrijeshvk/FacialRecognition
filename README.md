# Facial Recognition Based Attendance System

A Python-based attendance system that uses face recognition to automatically mark attendance.

## 🚀 Features
- Face detection using dlib
- Face recognition with ResNet model
- Automatic attendance marking
- Stores attendance in SQLite database
- Simple web interface

## 🛠️ Technologies Used
- Python
- dlib
- OpenCV
- SQLite
- Flask

## 📂 Project Structure
```
FacialRecognition/
│
├── templates/
├── data/
├── requirements.txt
├── app.py
└── README.md
```

## ⚙️ Setup Instructions

### 1️⃣ Clone the Repository

```
git clone https://github.com/imbrijeshvk/FacialRecognition.git
cd FacialRecognition
```

### 2️⃣ Create Virtual Environment

```
python -m venv venv
venv\Scripts\activate
```

### 3️⃣ Install Dependencies

```
pip install -r requirements.txt
```

### 4️⃣ Download Required Models

Download the following dlib models:

- shape_predictor_68_face_landmarks.dat  
- dlib_face_recognition_resnet_model_v1.dat  

From: http://dlib.net/files/

Place them inside:

```
data/data_dlib/
```

### 5️⃣ Run the Application

```
python app.py
```

## 📸 Screenshots
(Add screenshots here later)

## 📌 Note
Large model files and datasets are not included in this repository.

## 👨‍💻 Author
Brijesh Vishwakarma
