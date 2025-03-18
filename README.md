# 🚗 Vehicle Detection and Counting Tool

## ✨ Introduction

This project is a **Vehicle Detection and Counting Tool** that uses **OpenCV** and **Haar Cascade classifiers** to identify and count vehicles in images or video footage. It can be used for traffic analysis, surveillance, and monitoring vehicle movement.

## 🔧 Features

- ✅ Detects and counts vehicles in images and videos
- ✅ Uses OpenCV's **Haar Cascade Classifier** for vehicle detection
- ✅ Supports real-time and recorded video processing
- ✅ Customizable detection models

## 💻 Technologies Used

- ⚡ **Python**
- ⚡ **OpenCV**
- ⚡ **NumPy**
- ⚡ **PIL (Pillow)**
- ⚡ **Requests** (for fetching images from URLs)
- ⚡ **Flask** (for building the web app)

## 🛠️ Installation

### 🔧 Prerequisites

Ensure you have Python installed (✳ Version 3.6+ recommended). Install the required dependencies using:

```bash
pip install opencv-python numpy pillow requests flask
```

## 🚀 Running the Flask App

1. **Extract the ZIP File**:
   - 📂 Download and extract the provided ZIP file.

2. **Navigate to the Project Directory**:
   ```bash
   cd Detect-and-Count-Vehicle-Flask-App
   ```

3. **Run the Flask App**:
   ```bash
   python app.py
   ```

4. **Access the Web App**:
   - 🌍 Open your browser and go to: `http://127.0.0.1:5000/`

## 💡 Usage

1. **Run the Jupyter Notebook**:
   - 🔍 Open the provided `.ipynb` file in Jupyter Notebook or Google Colab.
   - 📚 Run the cells step by step to see the vehicle detection process.

2. **Modify Image or Video Source**:
   - 🎥 Update the image/video path in the code to use your own data.

3. **Customize Haar Cascade Model**:
   - 🔒 Replace the pre-trained Haar Cascade XML file with a different model for improved accuracy.

## 📸 Example Output

- 👉 **Input**: Traffic scene image
- 👈 **Output**: Image with detected vehicles highlighted and counted

## 🌐 Future Improvements

- 💡 Implement Deep Learning-based models like **YOLO** or **SSD** for better accuracy.
- 📽️ Add support for real-time detection using live camera feeds.

## ⚖️ License

This project is **open-source** and available for modification and enhancement.

