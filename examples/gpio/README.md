# GPIO Example

## Table of Contents

- [About](#about)
- [Getting Started](#getting_started)
- [How to use](#usage)

## About <a name = "about"></a>

Simple code to get started with ESP32 and ESP-IDF.
This test code shows how to configure GPIO and how to use GPIO interrupt.
For this test we use the [LILYGO® TTGO T-Display](http://www.lilygo.cn/prod_view.aspx?TypeId=50033&Id=1126&FId=t3:50033:3)

<img width="960" height="540" src="resources/gpio/pinout_ttgo"/>

## Getting Started <a name = "getting_started"></a>

### Prerequisites

- Visual Studio Code
- Esp-idf

### Installing

- [Download the latest release of this repository from the release page.](https://github.com/mectho/esp32/releases)
- move the "gpio" folder in the esp project folder.

## How to use <a name = "usage"></a>

- 1| [Follow these steps](https://github.com/mectho/esp32/tree/main/examples/hello_world#usage)
- 2| Configure GPIO using the instructions contained in Espressif [GPIO and RTC page](https://docs.espressif.com/projects/esp-idf/en/latest/esp32/api-reference/peripherals/gpio.html) 

 The original configurations set these parameters:
 * GPIO0:  input, pulled up, interrupt from falling edge.
 * GPIO35:  input, pulled up, interrupt from rising edge and falling edge

## License

Code released under the MIT License.
