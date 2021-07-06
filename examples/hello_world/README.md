# Hello World Example

## Table of Contents

- [About](#about)
- [Getting Started](#getting_started)
- [How to use](#usage)

## About <a name = "about"></a>

Simple code to get started with ESP32 and ESP-IDF.

Starts a FreeRTOS task to print "Hello World".


## Getting Started <a name = "getting_started"></a>

### Prerequisites

- Visual Studio Code
- Esp-idf


### Installing

- [Download the latest release of this repository from the release page.](https://github.com/mectho/esp32/releases)
- move the "hello_world" folder in the esp project folder.

## How to use <a name = "usage"></a>
1| Set up the environment variables and Launch Visual Studio Code 

Open Terminal, and run the following commands:

```
cd examples/hello_world/
get_idf
code .
```

<img width="960" height="540" src="/resources/hello_world/Console.png"/>
2| Select Device Port

<img width="960" height="540" src="/resources/hello_world/DevicePort.png"/>
3| <a href="https://docs.espressif.com/projects/esp-idf/en/latest/esp32/api-reference/kconfig.html">Configuration Tool (optional)</a> 

<img width="960" height="540" src="/resources/hello_world/ConfigurationTool.png"/>
4| Build

<img width="960" height="540" src="/resources/hello_world/Build.png"/>
5| Flash and Monitor

<img width="960" height="540" src="/resources/hello_world/FlashMonitor.png"/>

## License

Code released under the MIT License.
