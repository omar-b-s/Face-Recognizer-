# Face-Recognizer

Face Dataset Generator using Python and OpenCV. Captures faces from a webcam in real time, detects them with Haar Cascade, crops, resizes, and converts them to grayscale before saving up to 200 labeled samples per user (`data/user.<id>.<img_id>.jpg`). A live preview with counters makes it easy to monitor progress while building a reusable dataset for training facial recognition, security, or ML applications.

---

## ✨ Features
- Real-time face detection using Haar Cascade Classifier  
- Crops, resizes (200×200), and converts images to grayscale  
- Saves up to 200 labeled samples per user  
- Displays a live preview with an image counter  
- Creates reusable datasets for ML pipelines (facial recognition, attendance systems, etc.)

---

## ⚙️ Installation
Copy and paste these commands into your terminal:

```bash
# Clone the repository
git clone https://github.com/omar-b-s/Face-Recognizer.git
cd Face-Recognizer

# Install dependencies
pip install opencv-python opencv-python-headless
