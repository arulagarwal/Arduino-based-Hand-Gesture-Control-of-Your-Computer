# Arduino-based-Hand-Gesture-Control-of-Your-Computer
This project uses arduino to capture gestures which are interpreted by Python using PyAutOGUI

Arduino Circuit Design and implementation available on
https://www.tinkercad.com/embed/jkN9XT2fGc9?editbtn=1

The following are the 5 different hand gestures or actions that I’ve programmed for demonstration purpose.

Gesture 1: Place your hand in front of the Right Ultrasonic Sensor at a distance (between 15CM to 35CM) for a small duration and move your hand away from the sensor. This gesture will Scroll Down the Web Page or Decrease the Volume.

Gesture 2: Place your hand in front of the Right Ultrasonic Sensor at a distance (between 15CM to 35CM) for a small duration and move your hand towards the sensor. This gesture will Scroll up the Web Page or Increase the Volume.

Gesture 3: Swipe your hand in front of the Right Ultrasonic Sensor. This gesture will move to the Next Tab.

Gesture 4: Swipe your hand in front of the Left Ultrasonic Sensor. This gesture will move to the Previous Tab or Play/Pause the Video.

Gesture 5: Swipe your hand across both the sensors (Left Sensor first). This action will Switch between Tasks.

Based on the above mentioned gesture, the following Arduino Program has been written.
