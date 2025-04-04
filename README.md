# Drowsiness Detection System

A real-time Drowsiness Detection System built using OpenCV, Dlib, and machine learning techniques. This project is designed to monitor driver alertness by detecting signs of drowsiness such as prolonged eye closure and yawning, aiming to reduce road accidents caused by fatigue.

## 🚀 Features
- Real-time video stream processing
- Eye aspect ratio (EAR) based eye closure detection
- Yawn detection using lip distance
- Alarm system to alert drowsy drivers
- Simple and intuitive UI for monitoring

## 🛠️ Technologies Used
- Python
- OpenCV
- Dlib (for facial landmark detection)
- NumPy
- SciPy
- imutils

## 📦 Installation
```bash
# Clone the repository
git clone https://github.com/YourUsername/drowsiness-detection.git
cd drowsiness-detection

# Install dependencies
pip install -r requirements.txt
```

## 🧠 How It Works
1. The system captures real-time video from the webcam.
2. It detects facial landmarks using Dlib’s pre-trained models.
3. Eye aspect ratio (EAR) is calculated to determine eye closure.
4. If eyes remain closed for a defined threshold, an alarm is triggered.
5. Lip distance is also monitored to detect yawns.

## 📷 Screenshots
*Add relevant screenshots here showing the detection in action.*

## ⚙️ Usage
```bash
python drowsiness_detector.py
```

## 📈 Future Improvements
- Add deep learning models for more accurate detection
- Integrate with mobile or embedded systems for real-world deployment
- Add a GUI with Tkinter or PyQt for better user interaction

## 🧑‍💻 Author
Milind

## 📄 License
This project is licensed under the MIT License - see the LICENSE file for details.

