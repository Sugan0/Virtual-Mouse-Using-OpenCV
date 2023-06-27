# Virtual-Mouse-Using-OpenCV

# Virtual Mouse Using OpenCV
In this project we will be using the live feed coming from the webcam to create a virtual mouse using hand tracking.

## Project Description:
In this project, I am using my hand as a virtual mouse than can do everything that a mouse does without even touching your system. I am using the webcam of my system to detect my hands. It will then create a bounding box around my hand and focus on two fingers: The fore finger and the middle finger. The fore finger will act as a cursor and moving it around, we will be moving the cursor around. Now, inorder to successfully click using hand tracking, it is detecting the distance between the fore finger and the middle finger. If they are joined together, then it will perform a click.

# Requirements:
Following modules need to be installed for it to work properly:
- OpenCV
- Mediapipe
- Autopy
