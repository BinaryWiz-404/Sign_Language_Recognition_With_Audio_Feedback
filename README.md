# Sign_Language_Recognition_With_Audio_Feedback.
A real-time sign language detection system that uses computer vision and deep learning to recognize hand gestures and translate them into text with audio feedback for accessibility.
✨Features
Real-time sign language gesture detection using OpenCV and MediaPipe
Gesture recognition powered by TensorFlow
Converts recognized gestures into text in real-time
Audio feedback using Pyttsx3 for accessibility
Lightweight and works on most systems with a webcam

🛠️ Tech Stack
Python
OpenCV – Computer vision for video capture and image processing
MediaPipe – Hand landmark detection
TensorFlow – Model training and gesture classification
NumPy – Data handling and preprocessing
Pyttsx3 – Text-to-speech for audio output

📂 Project Structure
├── dataset/            # Collected gesture dataset
├── models/             # Trained TensorFlow models
├── scripts/            # Helper scripts (training, preprocessing)
├── main.py             # Main file to run the real-time detection
├── requirements.txt    # Project dependencies
└── README.md           # Project documentation

⚙️ Installation
1.Clone this repository
git clone https://github.com/your-username/sign-language-detection.git
cd sign-language-detection
2.Create a virtual environment (optional but recommended)
python -m venv venv
source venv/bin/activate   # Linux/Mac
venv\Scripts\activate      # Windows
3.Install dependencies
pip install -r requirements.txt

▶️ Usage
Run the real-time detection script:
python main.py
Show hand gestures in front of your webcam
Recognized gestures will be displayed as text and spoken aloud

🎯Future Improvements
Expand dataset to include more gestures
Add support for entire sign language sentences (not just single gestures)
Improve accuracy with more advanced deep learning architectures
Build a web-based or mobile version

