# Masked-Face-Recognition
Masked Face Detection and Recognition using MobileNet

Overview

This project focuses on masked face detection and recognition using MobileNet, a lightweight deep learning model optimized for mobile and embedded vision applications. The model is trained to identify faces with and without masks and perform accurate facial recognition.

Features

Detects masked and unmasked faces.

Recognizes individuals even with a mask.

Lightweight and optimized for real-time performance using MobileNet.

Can be integrated into surveillance systems, access control, and healthcare applications.

Technologies Used

Python (for scripting and model implementation)

TensorFlow / Keras (for deep learning)

OpenCV (for image processing)

MobileNet (for efficient face detection and recognition)

NumPy & Pandas (for data handling)

Matplotlib (for visualizing results)

Dataset

The model is trained on a combination of publicly available datasets containing images of masked and unmasked faces. Data augmentation techniques were applied to improve generalization.

Installation

Prerequisites

Ensure you have Python and necessary dependencies installed:

pip install tensorflow opencv-python numpy pandas matplotlib

Clone the Repository

git clone https://github.com/yourusername/masked-face-detection-mobilenet.git
cd masked-face-detection-mobilenet

Usage

1. Running the Model

Run the following script to detect masked faces in images or video streams:

python detect_mask.py

2. Training the Model

If you want to retrain the model with a new dataset:

python train.py

Model Performance

Accuracy: Achieves high accuracy in real-time detection.

Inference Speed: Optimized for fast processing using MobileNet.

Robustness: Performs well under various lighting conditions and occlusions.

Applications

Surveillance Systems: Identify masked individuals in CCTV footage.

Access Control: Masked face-based authentication.

Healthcare: Ensure mask compliance in public places.

Retail & Transportation: Contactless security verification.

Future Improvements

Improve accuracy on diverse ethnicities and lighting conditions.

Enhance real-time performance on edge devices.

Extend the model for multi-person masked recognition.

Contribution

Feel free to contribute by submitting pull requests or reporting issues!

License

This project is licensed under the MIT License.
