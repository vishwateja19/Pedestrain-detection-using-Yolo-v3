# Pedestrain-detection-using-Yolo-v3

This repository provides an implementation of YOLOv3 algorithm for pedestrain prediction  in videos using the Darknet framework.

![App Screenshot](https://viso.ai/wp-content/uploads/2021/02/YOLOv3-how-it-works.jpg)


![App Screenshot](https://hackaday.com/wp-content/uploads/2018/12/yolo-pedestrian-featured.png)




Requirements:
-
1.Darknet framework

2.Pre-trained YOLOv3 weights

3.OpenCV (cv2)

4.NumPy

5.Matplotlib













## Setup



Install the dependencies: pip install opencv-python numpy

Download the YOLOv3 weights file: yolov3.weights

Download the YOLOv3 configuration file: yolov3.cfg

Download the COCO dataset labels file: coco.names


## ACKNOWLEDGEMENT:

This implementation is based on the YOLOv3 implementation by Joseph Redmon. The COCO dataset is provided by Microsoft COCO.
## CUSTOMIZATION:

You can customize the detection parameters by modifying the object_detections.py script. The following parameters can be adjusted:

1.CONFIDENCE_THRESHOLD: Confidence threshold for detection (default: 0.5)

2.NMS_THRESHOLD: Non-maximum suppression threshold (default: 0.4)

3.YOLOV3_CONFIG_PATH: Path to YOLOv3 configuration file (default: yolov3.cfg)

4.YOLOV3_WEIGHTS_PATH: Path to YOLOv3 weights file (default: yolov3.weights)

You can also experiment with different object detection algorithms or train your own model to improve the accuracy of the detections.
## LICENSE:

This project is licensed under the MIT License - see the LICENSE file for details.
