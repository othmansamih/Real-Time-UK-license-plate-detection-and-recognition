# automatic-number-plate-recognition-python-yolov8

I developed a real-time system capable of detecting UK license plates within images and video streams, while also
extracting and reading the alphanumeric content in real time. The project integrates advanced computer vision and
machine learning techniques to achieve accurate and instantaneous recognition of UK license plates, showcasing
proficiency in real-time object detection and optical character recognition (OCR).

## data

The video I used in this project can be downloaded [here](https://drive.google.com/file/d/1YmHTElM6rh5uBpvaoUYpYTHK2odJkoM6/view?usp=drive_link).

## models

A Yolov8 pretrained model was used to detect vehicles.

A licensed plate detector was used to detect license plates. The model was trained with Yolov8 using [this dataset](https://universe.roboflow.com/roboflow-universe-projects/license-plate-recognition-rxg4e/dataset/4). <br>
The trained model is available [here](https://drive.google.com/file/d/1UtZCClx2A3KK9s4QuC4vQQdWlCSTSHW7/view?usp=sharing).

## dependencies

The sort module needs to be downloaded from [this repository](https://github.com/abewley/sort).
