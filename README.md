# 🎨 Color Detection and Object Counting using OpenCV  

This Python project detects **Red, Green, and Blue (RGB) objects** in real-time using a webcam and counts the number of detected objects for each color. The program uses **OpenCV and NumPy** for image processing.  

## 🛠 Features  
- 🟢 Detects **Red, Green, and Blue** objects in real-time  
- 📸 Uses **HSV color space** for accurate detection  
- 🔍 **Contours detection** to identify and count objects  
- 🏷️ Draws bounding boxes and labels around detected objects  
- 🖥 Displays the **real-time count** of detected objects on the screen  
- ⏳ Runs efficiently on **low-end computers**  

## 🎯 How It Works  
1. Captures video from the **webcam**  
2. Converts the video frames into the **HSV color space**  
3. Applies color masking to detect **Red, Green, and Blue** objects  
4. Identifies objects using **contour detection**  
5. Draws bounding boxes around detected objects  
6. Displays **live count** of detected objects on the screen  
7. Press **'q'** to exit the program  

## 🖥 Installation  
Follow these steps to run the project on your local machine:  

### 1️⃣ Clone the Repository  
```sh
git clone https://github.com/breweshank/Color-Detection-OpenCV.git
cd Color-Detection-OpenCV

### 2️⃣ Install Dependencies
```sh
pip install opencv-python numpy

