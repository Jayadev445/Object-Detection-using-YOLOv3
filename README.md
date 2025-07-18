# Object-Detection-using-YOLOv3

**Description:**

This project demonstrates how to perform real-time object detection using the YOLOv3 (You Only Look Once) deep learning model in Python with OpenCV. It identifies and classifies multiple objects in a single image and displays them with bounding boxes and labels. YOLOv3 is known for its speed and accuracy, making it suitable for applications such as autonomous vehicles, surveillance systems, and smart robotics.

**Technologies Used:**

Python 3.x

OpenCV

YOLOv3 (Darknet-53 architecture)

Pretrained COCO dataset

**Files and Structure:**

yolov3-object-detection/<br>
├── main.py               # Main script for object detection<br>
├── Dataset/<br>
│   ├── yolov3.cfg        # Model architecture<br>
│   ├── yolov3.weights    # Pre-trained weights<br>
│   └── coco.names        # List of class labels<br>
├── Input/<br>
│   └── sample.jpg        # Example input image<br>
├── Output/<br>
│   └── result.jpg        # Annotated image output<br>
├── README.md             # Project documentation<br>
└── requirements.txt      # Python dependencies<br>

**Download YOLOv3 Files:**

Place the following files into the Dataset/ folder:

[yolov3.cfg](https://github.com/pjreddie/darknet/blob/master/cfg/yolov3.cfg)

[yolov3.weights](https://www.kaggle.com/datasets/shivam316/yolov3-weights)

[coco.names](https://github.com/ayooshkathuria/pytorch-yolo-v3/blob/master/data/coco.names)
