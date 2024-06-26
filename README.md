# FaceRecognition
Overview
This project is a face recognition system developed using Python, OpenCV, and Haar Cascades. It can detect and recognize faces in real-time from a live video feed or from static images.

Features
Real-time face detection using webcam
Face recognition using Haar Cascades
Easy to use and modify for different use cases
Support for adding new faces to the recognition database
Requirements
To run this project, you'll need the following installed on your system:

Python 3.x
OpenCV
Numpy
Installation
Clone this repository to your local machine:
bash
Copy code
git clone https://github.com/yourusername/face-recognition-project.git

Navigate to the project directory:

bash
Copy code
cd face-recognition-project

Install the required packages:
bash

Copy code
pip install -r requirements.txt
Usage

Running the Face Recognition
To start the face recognition system, run the following command:
bash

Copy code
python face_recognition.py
Adding New Faces
Run the script to add new faces:
bash
Copy code
python add_face.py --name "Your Name"

Follow the instructions in the terminal to capture images of the new face.
Directory Structure
face_recognition.py: The main script to run the face recognition system.
add_face.py: Script to add new faces to the database.
haarcascade_frontalface_default.xml: Haar Cascade model for face detection.
dataset/: Directory where face images are stored.
trainer.yml: File where the trained model is saved.
requirements.txt: List of required packages.

Contributing
Contributions are welcome! If you'd like to contribute, please fork the repository and make changes as you'd like. Pull requests are warmly welcomed.

License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgements
OpenCV
Haar Cascades
