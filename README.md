# Electronic Gadget Detection using YOLOv8 and OpenCV

This project uses the YOLOv8 object detection model with OpenCV to detect specific electronic gadgets in real-time using a webcam. The system identifies objects like laptops, phones, remotes, and monitors by drawing bounding boxes and displaying labels with confidence scores.

## Features

- Real-time detection using YOLOv8 Nano
- Filters only relevant gadget classes
- Displays bounding boxes and confidence scores
- Simple keyboard exit mechanism

## Target Gadget Classes

- cell phone  
- laptop  
- remote  
- keyboard  
- mouse  
- tv  
- monitor  

## Requirements

Install the following Python packages:

```bash
pip install ultralytics opencv-python
Python 3.7 or higher is recommended.

Files
main.py: Python script for real-time gadget detection.

yolov8n.pt: YOLOv8n pretrained weights (automatically downloaded if not found).

How to Run
Make sure your webcam is connected.

Run the script using the following command:

python main.py
Press the q key to quit the application.

Description
The script captures webcam input and processes each frame through YOLOv8. It filters detections to include only electronic gadgets. Detected items are shown on the screen with bounding boxes and confidence values. Other detected items are logged in the console but not displayed on the screen.

Use Cases
Automated exam proctoring systems

Security camera systems with object monitoring

Electronic inventory control in workplaces

License
This project is open-source and available under the MIT License.

Acknowledgements
YOLOv8 by Ultralytics

OpenCV for real-time video processing
