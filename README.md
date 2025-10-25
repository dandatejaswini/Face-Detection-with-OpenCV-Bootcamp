# Face-Detection-with-OpenCV-Bootcamp
Day 2  Bootcamp project : Python script to detect faces in images using OpenCV and Haar Cascade classifiers. Demonstrates basic computer vision techniques.

**Project Overview:**  
This is a **Bootcamp project**, where we implemented a Python script to detect faces in images using **OpenCV** and **Haar Cascade classifiers**. This project demonstrates basic computer vision techniques, including image loading, grayscale conversion, and face detection.

---

## Technologies Used
- Python 3.x
- OpenCV (`opencv-python-headless`)
- NumPy
- Matplotlib

---

## How to Run the Code
1. Clone the repository:
   git clone https://github.com/YourUsername/Face-Detection-with-OpenCV-Bootcamp.git
2. Navigate to the project folder:
   cd Face-Detection-with-OpenCV-Bootcamp
3. Install required libraries (if not already installed):
   pip install opencv-python-headless matplotlib numpy
4. Run the script:
   python face_detection.py
   - The script will automatically download a sample image and the Haar cascade XML file.
   - Detected faces are highlighted with green rectangles.

---

## Sample Output
The program detects faces in an image and displays the result using Matplotlib:

![Face Detection Example](https://raw.githubusercontent.com/opencv/opencv/master/samples/data/lena.jpg)

---

## Notes
- You can replace the sample image URL in the code with any image of your choice.
- Adjust parameters like scaleFactor and minNeighbors in detectMultiScale() for different detection results.
- Ensure an active internet connection to download the Haar cascade XML and sample image.

---
