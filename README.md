# Personal Protective Equipment (PPE) Detection System

This project implements a real-time Personal Protective Equipment (PPE) detection system using the YOLOv8 object detection model. It processes video input to identify whether individuals are wearing essential safety gear such as hard hats, masks, and safety vests.

## Key Features:
- **Fast and Accurate Detection**: Utilizes YOLOv8 for real-time detection of PPE and other safety-related items with high accuracy.
- **Real-Time Video Processing**: Processes video streams using OpenCV, providing live feedback on PPE compliance.
- **Bounding Boxes and Confidence Scores**: Displays detected objects with bounding boxes and confidence scores to visually verify detection accuracy.
- **Color-Coded Alerts**: 
  - **Red**: Highlights missing PPE items (e.g., no hard hat, no mask, or no safety vest).
  - **Green**: Indicates correctly worn PPE, ensuring workers meet safety requirements.
- **Customizable Detection Classes**: The list of detectable objects can be customized to suit different workplace environments.
- **Enhanced Visual Display**: Integrates `cvzone` to provide visually appealing bounding boxes and text overlays for better user experience.

## Technologies Used:
- **Python**: Primary programming language for implementing the system.
- **YOLOv8**: Object detection model for identifying PPE and other objects in real-time.
- **OpenCV**: Used for video stream handling and frame processing.
- **cvzone**: A helper library for easier bounding box and text overlays, enhancing the overall user interface.
- **Computer Vision**: Applied for safety monitoring and object detection.

---
![Uploading image.png…]()
