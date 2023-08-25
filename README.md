# 🌊 Underwater Trash Plastic Detection 🛢️

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li><a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->
## 🌟 About The Project

We have developed an underwater trash plastic detection project using YOLOv5 and YOLOv8 by training custom datasets. This project includes two models: one based on YOLOv5 for object detection and another using YOLOv8 for instance segmentation.

### Built With

* YOLOv5
* YOLOv8

<!-- GETTING STARTED -->
## 🚀 Getting Started

We utilized Google Colab with GPU support to run our YOLOv5 model.

### Prerequisites

* Python

### Installation for YOLOv5 object detection

1. Clone the repository
   ```sh
   !git clone https://github.com/ultralytics/yolov5.git
   ```
2. Install required dependencies
   ```sh
   !pip install -r requirements.txt
   ```
3. Run the YOLOv5 object detection model
   ```sh
   !python detect.py --weights bestpla.pt --source path/to/folder/orImage
   ```
### Installation for YOLOv8 instance segmentation

1. Install ultralytics
   ```sh
   !pip install ultralytics
   ```
2. Install required dependencies
   ```sh
   !pip install -r requirements.txt
   ```
3. Run the YOLOv5 object detection model
   ```sh
   !yolo predict model='runs/segment/yolov8n-seg/weights/best.pt' source='detection source file' name='folder_name'
   ```
   

<!-- USAGE EXAMPLES -->
## 🎯 Usage
This project serves to detect underwater garbage, including items like plastic bags. It can contribute to ocean cleanup efforts and environmental monitoring.

To run the project, consider Google Colab.

<div align="center">
  <img src="output images/plastic-bag1.jpg" alt="Underwater waste detection image" width="400" height="400"/>
  <img src="output images/plastic-bag.jpg" alt="Underwater waste detection image" width="400" height="400"/>
  <img src="output images/plastic-cup.jpg" alt="Underwater waste detection image" width="400" height="400"/>
</div>

<!-- LICENSE -->
## 📜 License
Distributed under the MIT License. See `LICENSE` for more information.

<!-- ACKNOWLEDGEMENTS -->
## 🙏 Acknowledgments
Thanks to [Ultralytics](https://github.com/ultralytics) for their awesome framework!
