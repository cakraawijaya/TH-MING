[![Open Source Love](https://badges.frapsoft.com/os/v1/open-source.svg?style=flat)](https://github.com/ellerbrock/open-source-badges/)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg?logo=github&color=%23F7DF1E)](https://opensource.org/licenses/MIT)
![GitHub last commit](https://img.shields.io/github/last-commit/cakraawijaya/TH-MING?logo=Codeforces&logoColor=white&color=%23F7DF1E)
![Project](https://img.shields.io/badge/Project-ESP32-light.svg?style=flat&logo=espressif&logoColor=white&color=%23F7DF1E)
![Type](https://img.shields.io/badge/Type-Personal%20Experiment-light.svg?style=flat&logo=gitbook&logoColor=white&color=%23F7DF1E)

# TH-MING
This project is an Industrial IoT-based system for real-time temperature and humidity monitoring using the XY-MD02 sensor. The ESP32-S3 acts as an IoT gateway, reading sensor data through RS485 and Modbus RTU, then transmitting the data via Wi-Fi using MQTT. The data is processed by Node-RED, stored in InfluxDB, and visualized using Grafana.

<br><br>

## Project Requirements
| Part | Description |
| --- | --- |
| Development Board | ESP32 S3 DEVKIT C N16R8 |
| Code Editor | Visual Studio Code - PlatformIO IDE |
| Framework | Arduino |
| Driver | CP210X USB Driver |
| Platform Stacks | • Mosquitto MQTT Broker<br>• InfluxDB<br>• Node-RED<br>• Grafana |
| Communications Protocol | • RS485<br>• Modbus RTU (Remote Terminal Unit)<br>• Message Queuing Telemetry Transport (MQTT) |
| IoT Architecture | 4 Layer |
| Programming Language | C/C++ |
| Arduino Library | • WiFi (default)<br>• MQTT<br>• ArduinoJson<br>• ModbusMaster |
| Sensor | XY-MD02: Temperature & Humidity Sensor (x1) |
| Other Components | • Micro USB cable - USB type A (x1)<br>• Jumper cable (1 set)<br>• Socket female jack DC (x1)<br>• Adaptor DC 5V (x1)<br>• MAX485 TTL to RS-485 Converter (x1) |

<br><br>
