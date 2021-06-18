# Esp32

## Table of Contents

- [About](#about)
- [Getting Started](#getting_started)
- [How to use](#usage)

## About <a name = "about"></a>

<!--
MT Semseg Labeler is an annotation application which can be used to label images for semantic segmentation, It can generate the mask labeling file. 

-->
This repository contains the projects used and reworked by mectho for taking the first steps torwards the universe of microcontrollers
## Getting Started <a name = "getting_started"></a>


### Prerequisites
- Python 
- Git 
- CMake and Ninja build tools



For these examples we used the following boards:
- [LILYGO® TTGO T-Display ESP32 WiFi And Bluetooth Module Development Board](http://www.lilygo.cn/prod_view.aspx?TypeId=50033&Id=1126&FId=t3:50033:3)
- [ESP32-S2-Saola-1](https://docs.espressif.com/projects/esp-idf/en/latest/esp32s2/hw-reference/esp32s2/user-guide-saola-1-v1.2.html)
- [ESP32-CAM](https://randomnerdtutorials.com/esp32-cam-ai-thinker-pinout/)

<p float="left">
<img width="310" height="310" src="https://github.com/mectho/gitImages/blob/main/esp32/808b45ee-f288-4048-a4a9-b21a5d1c7e13.jpg"/>
<img width="310" height="310" src="https://github.com/mectho/gitImages/blob/main/esp32/ESP32-S2-SAOLA-1R.jpg"/>
<img width="310" height="310" src="https://github.com/mectho/gitImages/blob/main/esp32/DEBO_CAM_ESP32_001.jpg"/>
 </p>
 
<!--
- python3
- tk >= v3.6.9
- Pillow >= v5.1.0
-->
### Installing
1) [Esp-idf Get Started](https://docs.espressif.com/projects/esp-idf/en/latest/esp32/get-started/index.html)
2) [Development Environment (VCode esp-idf extension)](https://github.com/espressif/vscode-esp-idf-extension/blob/master/docs/tutorial/install.md)
<!--
- [Download the latest release of this program from the release page.](https://github.com/Mectho/mt-semseg-labeler/releases)
- Launch mt_semseg_labeler.py
-->

## How to use <a name = "usage"></a>
<!--
The images must be placed within a folder along with a json file, named classes.json, where the user must indicate the different classes and the related mask pixel values.

in the example, the content of classes.json is:
```json
{
"orange":10,
"banana":15,
"apple":20,
"pear":25,
"kiwi":30,
"coconut":35,
"medlar":40,
"mango":45
}
```

The outcome of the labeling is a new 8-bit unsigned image with the same dimensions of the original image, of which the pixel values correspond to the selected  classes (the specific values are defined in the file classes.json).
-->
<!--#### First Steps
1| Launch the program -->

<!-- <img width="640" height="360" src="https://github.com/mectho/gitImages/blob/main/mt_semseg_labeler/ms-semseg%201.png"/>  -->


## License

Code released under the MIT License.
