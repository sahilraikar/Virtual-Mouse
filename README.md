# Virtual-Mouse

Dependencies: opencv-python(cv2), mediapipe, numpy, time, autopy, pyautogui


Note: change the fps = 1/(ctime-ptime) if the program crashes to a fps value relevant to your webcam characteristics

### Algorithm:
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

### Gestures
![image](https://user-images.githubusercontent.com/86056198/166639704-d948d58f-1522-41d6-a267-db859eb7a4fe.png)
21 hand landmarks

![image](https://user-images.githubusercontent.com/86056198/166639711-81ec7b39-7a45-4906-83b6-07963c74fb07.png)
Scroll up

![image](https://user-images.githubusercontent.com/86056198/166639728-8266b380-479d-4095-ae20-3615f0532604.png)
Scroll down

![image](https://user-images.githubusercontent.com/86056198/166639741-118d6cee-cdca-4436-9835-4609a0b0597f.png)
Left click

![image](https://user-images.githubusercontent.com/86056198/166639749-3430cf6d-6ffc-4b3c-9529-4bd425a913b7.png)
Drag and Drop

![image](https://user-images.githubusercontent.com/86056198/166639759-b90b89c4-2ede-4e13-b4e0-4d9d1bc5093c.png)
Pointer movement
