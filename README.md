# FACE_RECOGNITION_WITH_ARDUINO_UNO
HERE this is my BTech project in which I'm interfacing Arduino UNO with LCD(16*2) with Face Recognition

# Requirements

- Arduino Uno (I've used Arduino UNO R3)
- Arduino IDE
- Python (any version) #I'm using 3.++ version
- Visual Studio Desktop Development Tools
- cMake

## Python Modules
- OpenCV
- Dlib (need to have cMake installed to install ***dlib***)
- Face_recognition
- PySerial

# How to use

- Clone the repository
- Upload **ard_chaser.ino** to arduino board
- Change Serial name in **Face_Rec** under:
  **ArduinoConn = serial.Serial("change here", 9600)** #mine port is COM3
- Run **Face_Rec**
