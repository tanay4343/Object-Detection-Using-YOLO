
# Object Detection Using YOLO

This repository provides resources and tools for understanding and implementing object detection using the YOLO (You Only Look Once) algorithm. YOLO is a state-of-the-art real-time object detection system that is fast and accurate.






## Features

- Real-time Detection: YOLO can detect objects in real-time with high accuracy.
- Single Network: It treats object detection as a regression problem to spatially separated bounding boxes and associated class probabilities.
- Versatility: Suitable for various applications including autonomous driving, surveillance, and robotics.



## Installation

Clone the repository:

```bash
  https://github.com/tanay4343/Object-Detection-using-YOLO.git
  gh repo clone tanay4343/Object-Detection-using-YOLO
```
Install dependencies:
```bash
pip install -r requirements.txt

```

## Usage
1. Prepare Your Dataset: Organize your dataset with annotated images and corresponding labels.

2. Configure YOLO: Adjust YOLO configuration files (yolov3.cfg, yolov4.cfg) based on your requirements.

3. Train YOLO: Start training the model using the prepared dataset.

```bash
python train.py --data path/to/data --cfg cfg/yolov3.cfg --epochs 100
```


## Contributing

Contributions are welcome! If you have improvements or suggestions, feel free to open an issue or create a pull request.


