# Exercise-Posture-Corrector
Welcome to the Posture Corrector project repository! This project applies machine learning and computer vision to analyze and improve exercise form for users performing workouts at home or without supervision. By detecting common posture errors during exercises, the system ensures safer and more effective fitness routines.

Overview
Project Goal
To develop machine learning models capable of detecting and correcting posture errors in four popular exercises:

Bicep Curl
Plank
Squat
Push-up
Core Technologies
MediaPipe: For real-time human pose detection.
TensorFlow/Keras: For building and training neural network models.
Scikit-learn: For classical machine learning methods.
Gradio: For creating an interactive user interface.
Features
Error Detection: Identifies incorrect form for specific exercises using predefined thresholds or trained machine learning models.
Detailed Feedback: Provides insights on form deviations and correction suggestions.
Interactive Interface: A user-friendly web application to analyze video inputs and display feedback.
Customizable Models: The system supports retraining and extension to other exercises.
Repository Structure
plaintext
Copy code
.
├── data/                    # Dataset and preprocessing scripts
├── models/                  # Trained models for error detection
├── src/                     # Core implementation code
├── ui/                      # Gradio-based user interface code
├── results/                 # Evaluation metrics and test results
└── docs/                    # Project report and documentation
Getting Started
Prerequisites
Python 3.7+
Libraries: TensorFlow, Keras, MediaPipe, OpenCV, Gradio, NumPy, Pandas, Scikit-learn, Matplotlib, Seaborn.
Installation
Clone this repository:
bash
Copy code
git clone https://github.com/your-repo/posture-corrector.git
Navigate to the project directory:
bash
Copy code
cd posture-corrector
Install dependencies:
bash
Copy code
pip install -r requirements.txt
Usage
Launch the user interface:
bash
Copy code
python src/app.py
Upload a video of an exercise.
Select the exercise type for analysis.
Receive detailed feedback on posture errors and suggestions for improvement.
Methodology
Pose Detection: Utilizes MediaPipe to extract landmarks.
Error Metrics: Calculates angles, distances, and other geometric features to identify incorrect form.
Model Training: Employs neural networks and classical ML techniques for robust classification.
For detailed methodology, refer to the project report.

Results
Highlights
Bicep Curl: Detected loose upper arm, weak peak contraction, and leaning back.
Plank: Identified sagging or elevated lower back positions.
Squat: Detected foot and knee misalignments.
Push-up: Noted hip sagging, incorrect elbow angles, and high back position.
For evaluation metrics, check the results directory.

Future Work
Expand dataset diversity to include varied body types and fitness levels.
Add more exercises and error categories.
Implement automated exercise detection for seamless analysis.
