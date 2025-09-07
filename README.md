#  Invisibility Cloak

My very first OpenCV project inspired by the famous **Harry Potter invisibility cloak**!  
This project uses **Python** and **OpenCV** to make you disappear in real time using just your webcam and a colored cloak.  


##  About the Project
I’ve always been fascinated by computer vision and this project gave me the chance to dive into OpenCV for the first time. The idea is simple but magical:  
- Wear a cloak of a specific color (default: red).  
- The program detects that color and replaces it with the captured background.  
- Result: You look invisible   

This project taught me how to:  
- Work with **color spaces (BGR → HSV)**.  
- Use **masks and bitwise operations** in OpenCV.  
- Handle **real-time video processing** with a webcam.  


##  Features
- 🎥 Real-time webcam processing  
- 🎨 Detects a user-defined cloak color  
- 🪄 Creates an invisibility illusion by replacing cloak pixels with the background  
- 🧑‍💻 Beginner-friendly and fun computer vision project  



##  Tech Stack
- **Python**  
- **OpenCV (cv2)**  
- **NumPy**



## How It Works
1. Capture the background before the subject enters the frame.  
2. Convert video frames from **BGR → HSV color space**.  
3. Define HSV range for the cloak color (e.g., red).  
4. Generate a mask to detect the cloak.  
5. Replace those pixels with the background.  
6. Merge the final output to show the illusion of invisibility.  
