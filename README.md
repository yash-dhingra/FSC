# FSC
FSC(Face Gesture Control)


Greeting(s)

In order for you to use this program you must have the following installed on your computer :-

1. Python
2. OpenCV library for python.
3. Numpy
4. Pynput

Ensure that you have downloaded both the python (MainFGC.py) and the XML(Haarcascade) file. Note* I do not own the haarcascade nor have created it, you may download it from anywhere but do note that you might need to change the values (Detect Multi Scale) accordingly. 

Make sure you have dowloaded all the necessary files.

After extracting the files, follow these steps-
1. Ensure that all the content is in the same folder.
2. Open MainFGC.py
3. Then delete the XML file path(7th Line) and replace it with your XML(Hand.xml) file path you just downloaded.
4. Huzza! Now all that's left is to run the Program in the backgroud and open the game(Example T-rex(Chrome Game)).
Note* Ensure that the camera window is visible on the screen 

The middle lower area is the neutral area. If the program does not detect your hand it will pause the game(Emulate Key 'P').

Error You Might Encounter:-
If the program window does not turn on the Webcam/Webcam video is not visible, then try changing the camera port.(Usually 0 for Laptop's/Inbuilt Webcam(s)) in line 6(cap = cv2.VideoCapture(x)); where x is the camera port.
