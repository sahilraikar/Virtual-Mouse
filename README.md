# Virtual-Mouse

Dependencies: opencv-python(cv2), mediapipe, numpy, time, autopy, pyautogui


Note: change the fps = 1/(ctime-ptime) if the program crashes to a fps value relevant to your webcam characteristics

Algorithm:
1. Capturing an image from the webcam feed 
2. Converting the captured image from BGR to RGB 
3. Sending the RGB image to the hand detection module
4. Hand detection module detects 21 hand landmarks
5. Converting the landmarks into pixel coordinates 
6. Sending the list of coordinates to the main program
7. Calculating the distances between the required landmarks
8. Placing the mouse pointer according to the coordinates and performing the required action



### Instructions-
1. install pycharm
2. use python3.7
3. install opencv - pip install opencv-python
4. install mediapipe - pip install mediapipe
5. install autopy - pip install autopy
6. install pyautogui - pip install pyautogui
