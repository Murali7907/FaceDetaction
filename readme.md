Face Detection using OpenCV
This project demonstrates a simple face detection application using the OpenCV library in Python. It captures video from the default webcam, detects faces in real-time, and draws rectangles around them.

Requirements
Python 3.x
OpenCV library (cv2)
Installation
Ensure you have Python installed on your system. Install the required library using:

bash
Copy code
pip install opencv-python
Usage
Run the Script:

Execute the following command to run the face detection script:

bash
Copy code
python face_detection.py
Exit the Application:

Press 'q' to exit the application.

Code Overview
The main script (face_detection.py) consists of the following key components:

Haar Cascade Classifier:

Initializes the Haar cascade classifier using the pre-trained face detection model.
Video Capture:

Opens a connection to the default camera (index 0).
Face Detection Loop:

Captures frames from the webcam feed.
Converts frames to grayscale for face detection.
Utilizes detectMultiScale to identify faces in the frame.
Draws rectangles around detected faces.
Display:

Uses cv2.imshow to display the frame with face rectangles.
Exit Mechanism:

Waits for a key press. If 'q' is pressed, the application exits.
Resource Release:

Releases the video capture object.
Closes all OpenCV windows.
Customization
Feel free to modify and extend the code to suit your specific needs. You can experiment with different Haar cascade classifiers for improved face detection or incorporate additional features such as facial recognition.

Acknowledgments
This project relies on the OpenCV library and Haar cascade classifiers for face detection.