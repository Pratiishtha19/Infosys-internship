# 🤖 AI Visual Analytics Platform

## 📌 Project Overview

The **AI Visual Analytics Platform** is an AI-based object detection application developed using **Python, YOLOv8, Streamlit, and Pillow**.

The application allows users to upload an image and uses the **YOLOv8 object detection model** to identify objects present in the image. The detected objects are displayed with bounding boxes along with their confidence scores.

## 🎯 Objective

The objective of this project is to understand the fundamentals of **computer vision and object detection** and learn how to integrate a pre-trained AI model into an interactive web application.

## ✨ Features

* 📤 Upload images in JPG, JPEG, and PNG formats
* 🤖 Detect objects using YOLOv8
* 🖼️ Display the uploaded image
* 🔍 Display the image with detected objects
* 📦 Show bounding boxes around detected objects
* 📊 Display detected object names
* 📈 Display confidence scores
* 🌐 Interactive interface using Streamlit

## 🛠️ Technologies Used

| Technology             | Purpose                               |
| ---------------------- | ------------------------------------- |
| **Python**             | Main programming language             |
| **Streamlit**          | Creates the interactive web interface |
| **Ultralytics YOLOv8** | Performs object detection             |
| **Pillow (PIL)**       | Opens and handles uploaded images     |

## 🧠 YOLOv8

This project uses the **YOLOv8n (YOLOv8 Nano)** pre-trained model from Ultralytics.

YOLO (**You Only Look Once**) is an object detection algorithm that can identify multiple objects in an image and determine their locations.

The model processes the uploaded image:

```python
results = model(image)
```

The detection results contain information about the detected objects, including their:

* Class
* Location/bounding box
* Confidence score

## 🔄 Application Workflow

```text
        User uploads an image
                 ↓
        Streamlit receives image
                 ↓
        Pillow opens the image
                 ↓
          YOLOv8 processes it
                 ↓
          Objects are detected
                 ↓
       Bounding boxes are created
                 ↓
      Detection result is displayed
                 ↓
 Object names & confidence scores
          are displayed
```

## 📂 Project Structure

```text
AI-Visual-Analytics-Platform/
│
├── milestone 1.py
├── requirements.txt
└── README.md
```

## ⚙️ Installation

### Step 1: Clone the repository

```bash
git clone YOUR_GITHUB_REPOSITORY_LINK
```

### Step 2: Open the project folder

```bash
cd AI-Visual-Analytics-Platform
```

### Step 3: Install the required libraries

```bash
pip install -r requirements.txt
```

The `requirements.txt` file contains:

```text
streamlit
ultralytics
pillow
```

## ▶️ How to Run

Run the following command in the terminal:

```bash
streamlit run "milestone 1.py"
```

The Streamlit application will open in your web browser.

## 📸 Screenshots

### Upload Image

Add a screenshot of the application showing the uploaded image.

### Object Detection Result

Add a screenshot showing the detected objects with bounding boxes and confidence scores.

## 📚 Concepts Learned

Through this project, I gained practical knowledge of:

* Python programming
* Image processing and image handling
* Computer Vision fundamentals
* Object Detection
* YOLO and YOLOv8
* Pre-trained AI models
* Bounding boxes
* Confidence scores
* Ultralytics library
* Streamlit
* Integrating AI models with web applications
* Handling user-uploaded files

## 🎓 Internship Learning

This project helped me understand how **AI and Computer Vision concepts can be implemented in a practical application**.

I learned how to use a pre-trained YOLOv8 model for object detection and integrate it with Streamlit to create an interactive application where users can upload images and view AI-generated detection results.

## 👤 Author

**Pratishtha Gadwanshi**
Technocrats Institute of Technology
