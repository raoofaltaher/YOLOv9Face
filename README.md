# YOLOv9Face: High-Performance Face Detection

Welcome to **YOLOv9Face**, a state-of-the-art face detection system based on the YOLOv9 architecture, specially trained on the WIDER FACE dataset to provide high accuracy and real-time performance across diverse scenarios.

## Features

- **State-of-the-Art Accuracy:** Utilizes the powerful YOLOv9 architecture, fine-tuned for face detection to ensure high precision across various environments.
- **Real-Time Detection:** Designed for efficiency, enabling real-time face detection on both high-end GPUs and edge devices.
- **Robust and Reliable:** Excellently handles challenging conditions such as low light, occlusions, and varied face orientations.
- **Ease of Use:** Simple setup and integration process, perfect for both standalone applications and integration into existing systems.
- **Open Source and Customizable:** Fully open-source for easy customization and further improvement on different datasets.

## Getting Started

### Prerequisites

Ensure you have Python 3.8+ and pip installed on your system.

### Installation

Clone this repository and install the required dependencies:

- git clone https://github.com/raoofaltaher/YOLOv9Face.git
- git clone https://github.com/WongKinYiu/yolov9
- cd YOLOv9Face
- pip install -r requirements.txt


### Quick Start

To detect faces in an image using a pretrained model
- python detect.py --source path/to/your/image.jpg

## Citation

```
@article{wang2024yolov9,
  title={{YOLOv9}: Learning What You Want to Learn Using Programmable Gradient Information},
  author={Wang, Chien-Yao  and Liao, Hong-Yuan Mark},
  booktitle={arXiv preprint arXiv:2402.13616},
  year={2024}
}
```

```
@article{chang2023yolor,
  title={{YOLOR}-Based Multi-Task Learning},
  author={Chang, Hung-Shuo and Wang, Chien-Yao and Wang, Richard Robert and Chou, Gene and Liao, Hong-Yuan Mark},
  journal={arXiv preprint arXiv:2309.16921},
  year={2023}
}
```

## Reference
* [YOLOv9](https://github.com/WongKinYiu/yolov9) - YOLOv9: Learning What You Want to Learn Using Programmable Gradient Information
* [WIDER FACE](http://shuoyang1213.me/WIDERFACE) - WIDER FACE: A Face Detection Benchmark
* [YOLO5Face](https://github.com/deepcam-cn/yolov5-face)


## Credits
* https://github.com/spacewalk01/yolov9-face-detection
* https://github.com/WongKinYiu/yolov9
* https://github.com/deepcam-cn/yolov5-face
