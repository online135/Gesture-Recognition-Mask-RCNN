# Gesture-Recognition-Mask-RCNN
Implement Real-Time Gesture-Recognition and Segmentation with [Mask_RCNN](https://github.com/matterport/Mask_RCNN).

## Requirements
- Ubuntu 16.04
- Python 3.5
- Tensorflow-gpu 1.8
- Keras 2.1.6
- OpenCV 3.4

## Getting Started
Creating virtualenv
```bash
$ cd Gesture-Recognition-Mask-RCNN
$ virtualenv env --python=python3.5
$ source env/bin/activate
```

Install Dependencies
```bash
$ pip install -r requirements.txt
```

Download pre-trained Gesture weights (mask_rcnn_gesture_0001.h5) from the [Google Drive](https://drive.google.com/open?id=1g-E1VEMBgDblF7U-ME0dcTfdEE7q96PK).

Run Demo
```bash
$ python demo.py \
    --input_model=YOUR_MODEL_PATH \
    --input_video=YOUR_VIDEO_PATH
```
<div align='center'>
  <img src='img/demo.gif' width='550px'>
</div>
