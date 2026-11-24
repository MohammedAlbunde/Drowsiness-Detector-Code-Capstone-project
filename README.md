# Drowsiness Detector

Engineering Capstone Project | Conestoga College | Embedded Systems Development

A real-time driver drowsiness detection system. It monitors the driver's eyes
through a camera, and if the eyes stay closed for more than 3 seconds it sounds
an alarm, sends an SMS and an email notification, and logs the event to the
cloud so alert history can be visualized.

## How It Works
1. The camera captures video of the driver's face.
2. Facial landmarks are detected and the eye aspect ratio is computed.
3. If the eyes remain closed for more than 3 seconds, an audible alarm plays.
4. Each alarm triggers an SMS and an email notification.
5. Each event is uploaded to ThingSpeak, which plots a graph of the alarms.

## Technologies
- **Computer vision:** Python, OpenCV, dlib, SciPy, imutils
- **Alerts:** playsound (audio alarm), smtplib (email), SMS gateway
- **Connectivity:** Bluetooth
- **Cloud and IoT analytics:** ThingSpeak, urllib.request

## Status
Capstone project built, tested and demonstrated as part of the Embedded Systems
Development program at Conestoga College. Source code is not published in this
repository.

## Author
Mohammed Al-Bunde
[LinkedIn](https://www.linkedin.com/in/mohammed-al-bunde)
