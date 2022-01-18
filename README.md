# under-water-trash-plastic-detection

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
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
## About The Project

we built a under water trash plastic detection project with the use of yolov5 by using our custom dataset

### Built With

* yolov5


<!-- GETTING STARTED -->
## Getting Started

we used google colab to run our yolov5 model to run it with gpu

### Prerequisites

* python

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/ultralytics/yolov5.git
   ```
2. Install required dependensies
   ```sh
   pip install -r requirements.txt
   ```
3. Enter this command to detect the vehicle images
   ```js
   !python detect.py --weights bestpla.pt --source path/to/folder/orImage
   ```

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- USAGE EXAMPLES -->
## Usage

* we can use this project to detect the presence of garbage inside our oceans like plastic bags.
* [google colab](https://colab.research.google.com/drive/1Ymz1JBISuL9pDHKpD70IQahm-WxIltkn) will be helpful to run the project 


<img src="output images/plastic-bag1.jpg" alt="underwater waste detection image" width="800" height="800"/>   <img src="output images/plastic-bag.jpg" alt="underwater waste detection image" width="400" height="400"/> <img src="output images/plastic-cup.jpg" alt="underwater waste detection image" width="400" height="400"/>

<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.


<!-- CONTACT -->
## Contact

* Mayur Asodara - [linkedIn profile](https://www.linkedin.com/in/mayur-asodara-366067206), email_id - mayurasodara@gmail.com

Project Link: [https://github.com/mayuras7685/Under-water-trash-plastic-detection.git](https://github.com/mayuras7685/Under-water-trash-plastic-detection.git)



<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements
* [Ultralytics/yolov5](https://github.com/ultralytics/yolov5)

