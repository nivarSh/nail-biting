# nail-biting
 Python Script to prevent nail biting by tracking hand & face data

 # Overview
 Python script that leverages the mediapipe pre-trained machine learning library to extract hand and facial data. Once the tracking is completed (frame by frame) the script analyzes the face data and extracts the mouth coordinates and the finger coordinate. It checks the euclidean distance to determine how close the fingertip is to the mouth. Once it passes the distance threshold, it displays a message to notify the user that their finger is close to the mouth. 

 # Further Improvements
 - Deploy this script on the web so others can use it for preventing their nail biting habits
 - Learn performance boosting techniques to run application more efficently, to make app more accessible to slower computers

