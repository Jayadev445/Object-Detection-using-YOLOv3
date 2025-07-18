# Object-Detection-using-YOLOv3

Description:
This project demonstrates how to perform real-time object detection using the YOLOv3 (You Only Look Once) deep learning model in Python with OpenCV. It identifies and classifies multiple objects in a single image and displays them with bounding boxes and labels. YOLOv3 is known for its speed and accuracy, making it suitable for applications such as autonomous vehicles, surveillance systems, and smart robotics.

Technologies Used:
Python 3.x

OpenCV

YOLOv3 (Darknet-53 architecture)

Pretrained COCO dataset

Files and Structure:

yolov3-object-detection/
├── main.py               # Main script for object detection
├── Dataset/
│   ├── yolov3.cfg        # Model architecture
│   ├── yolov3.weights    # Pre-trained weights
│   └── coco.names        # List of class labels
├── Input/
│   └── sample.jpg        # Example input image
├── Output/
│   └── result.jpg        # Annotated image output
├── README.md             # Project documentation
└── requirements.txt      # Python dependencies

Download YOLOv3 Files:

Place the following files into the Dataset/ folder:

yolov3.cfg

yolov3.weights

coco.names
