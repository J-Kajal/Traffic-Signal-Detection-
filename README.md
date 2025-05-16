🚦 Traffic Signal Identifier using CNN with Voice Alerts

This project is a voice alert-based system that identifies and classifies traffic signals (Red, Yellow, Green) from images or live video feeds and *generates voice-based alerts* utilizing text-to-speech. It is implemented using *Python, **YOLOv5, **OpenCV, and **pyttsx3* for voice output.



🧠 Overview

In contemporary traffic infrastructure, visual detection of signals might not be enough — particularly for visually challenged humans or autonomous vehicles requiring audio notification. This project builds on existing traffic signal recognition by combining *Convolutional Neural Networks (CNNs)* with *voice notifications* that declare the identified signal status.

---

Key Features

- ✅ Real-time traffic light detection (Red, Yellow, Green)
-  Image classification via deep learning through CNN (e.g., YOLOv5)
-  Voice output with pyttsx3 to read out the current signal
-  Compensates for changing lighting/weather conditions and occlusions
-  Operates on webcam or pre-recorded video input

---
 Project Objectives

- Enhance traffic safety through both visual and voice signal recognition
- Enable autonomous systems and visually impaired users
- Develop an intelligent, dynamic traffic light detector for real-world implementation

---

🛠 Tools & Technologies


| Category         | Technology                     |
|------------------|--------------------------------|
| Language         | Python                         |
| Deep Learning    | TensorFlow / PyTorch, YOLOv5   |
| Computer Vision  | OpenCV                         |
| Text-to-Speech   | Pyttsx3                        |
| IDE              | Visual Studio Code             |
| OS               | Windows 11                      |

---


🧪 Testing & Results


| Test Scenario                         | Result      | Accuracy   |
|--------------------------------------|-------------|------------|
| Standard signal in clear image       | ✅ Pass     | > 95%      |
| Low light or night scenes        | ✅ Pass     | > 85%      |
| Occluded or partially occluded signal  | ⚠ Partial  | > 70%      |
| Heavy occlusion or unseen designs   | ❌ Fail     | < 50%      |
| Video with moving objects & light    | ⚠ Partial  | ~65%       |

Voice output examples:
- "Red signal in front, stop please."
- "Yellow signal found, get ready."
- "Green signal, go with care."

---

 🚀 Future Scope

-  Mobile variant with voice notifications
-  ADAS and autonomous system integration
-  Support for IoT-enabled connected traffic management
-  Multilingual voice output

---
👨‍💻 Contributors
- Parshwa Dedhia (08)
- Kajal Jagtap (14)

Guided by: Assistant Prof. Seema Bhuravane

---

📚 References

1. YOLOv5 for real-time object detection
2. OpenCV for computer vision
3. Pyttsx3 for offline text-to-speech in Python
4. Research articles on traffic signal recognition and CNNs
