# 🧠 Mini Face Recognition System (Bhagat Singh & Shivaji Maharaj)

This is a **mini face recognition project** developed in **Python using PyCharm**, which recognizes two specific historical figures: **Bhagat Singh** and **Chhatrapati Shivaji Maharaj**. Any other face is flagged as "Not Recognized." It uses the `face_recognition` and `OpenCV` libraries to verify identities from images.

---

## 🎯 Objective

- Recognize faces of Bhagat Singh and Chhatrapati Shivaji Maharaj.
- Reject unregistered faces by displaying "Not Recognized".
- Demonstrate how a minimal face verification system can be implemented using Python.

---

## 🧾 Dataset

- **Known Faces**: 
  - bhagat_singh.jpg
  - shivaji_maharaj.jpg
- **Test Images**:
  - Any image containing one or more faces (either known or unknown).

> All images should be placed in appropriate folders (e.g., `images/` and `test_images/`).

---

## 🧰 Technologies Used

- Python 3.x
- [face_recognition](https://github.com/ageitgey/face_recognition)
- OpenCV (cv2)
- NumPy
- PyCharm (for development)

---

## 🚀 How to Run the Project

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/mini-face-recognition.git
   cd mini-face-recognition
Install dependencies

bash
Copy
Edit
pip install face_recognition opencv-python numpy
Run the script

bash
Copy
Edit
python recognizer.py
🧪 Output Behavior
If a known face is detected:

yaml
Copy
Edit
Detected Face: Bhagat Singh
If an unknown face is detected:

yaml
Copy
Edit
Detected Face: Not Recognized
📸 Sample Use Case
A person holds a mobile phone showing Bhagat Singh's photo in front of a webcam. The Python code running in PyCharm captures the video frame, detects the face, and displays:

yaml
Copy
Edit
Face Recognized: Bhagat Singh
The webcam window will also show the name overlayed on the detected face box.

📝 Code Overview
Load known faces and encode them.

Capture or load test image(s).

Compare test face encodings with known faces.

Display recognized names or "Not Recognized".

📁 Folder Structure
css
Copy
Edit
mini-face-recognition/
│
├── images/
│   ├── bhagat_singh.jpg
│   └── shivaji_maharaj.jpg
│
├── test_images/
│   └── input.jpg
│
├── recognizer.py
├── README.md
└── requirements.txt
🔮 Future Enhancements
Add support for webcam-based real-time face recognition.

Add more historical figures to the face database.

Export results as a log file or display match confidence scores.

📄 License
This project is licensed under the MIT License. See the LICENSE file for details.

👤 Author
Your Name
GitHub: @yourusername

yaml
Copy
Edit
