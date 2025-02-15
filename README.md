# KMP ProDino ESP32 examples library

Welcome in our our library page. Here you can find a lot of examples how to use our board.

Forked from https://github.com/kmpelectronics/ProDinoESP32

## Changes
- [WebRelayWE.ino](./examples/WebRelayWE/WebRelayWE.ino) - optional WIFI support (#define WIFI_TEST)
- support to set hostname for Ethernet when using DHCP


## How to install our library

 -   
    Downloading and saving the file "**[ProDinoESP32.zip](https://github.com/kmpelectronics/ProDinoESP32/releases/download/2.0.0/ProDinoESP32.zip?raw=true)**" on your desktop
 -     
    Opening your Arduino IDE. From the menu selects:  **Sketch**  >  **Include Library**  >  **Add .ZIP Library...**
 -    
    Select the zip file "ProDinoESP32.zip" from your desktop and click  **Open**
 -    
    You can see our examples in: File > Examples > (Section: Examples from Custom Libraries)  **ProDino_ESP32**
## Examples
All examples have suffix. Every suffix is linked with which communication channel the example uses for connection. The legend: **W** - WiFi, **E** - Ethernet, **G** - GSM. Some examples can use with only specific board. Some example can use more then one connection for example **WE** - you can connect this board both **WiFi** and **Ethernet**.
 - [AllE.ino](./examples/AllE/AllE.ino) includes all Web examples by communication through RS485, turning On/Off relays, reading isolated inputs, measuring temperature and humidity with DHT22 sensor. It uses Ethernet.
 - [AllW.ino](./examples/AllW/AllW.ino) includes all Web examples by communication through RS485, turning On/Off relays, reading isolated inputs, measuring temperature and humidity with DHT22 sensor. It uses WiFi.
 - [AllWE.ino](./examples/AllWE/AllWE.ino) includes all Web examples by communication through RS485, turning On/Off relays, reading isolated inputs, measuring temperature and humidity with DHT22 sensor. It uses WiFi and/or Ethernet.
- [AllWEG.ino](./examples/AllWEG/AllWEG.ino) includes all Web examples by communication through RS485, turning On/Off relays, reading isolated inputs, measuring temperature and humidity with DHT22 sensor also and Blynk example. It uses WiFi and/or Ethernet and/or GSM (with Blynk). 
- [BlynkG.ino](./examples/BlynkG/BlynkG.ino) Blynk example which use GSM for communication.
- [BlynkWE.ino](./examples/BlynkWE/BlynkWE.ino) Blynk example which use both or either WiFi and/or Ethernet for communication.
- [MqttSimpleG.ino](./examples/MqttSimpleG/MqttSimpleG.ino) MQTT simple example which use GSM for communication.
- [RS485Echo.ino](./examples/RS485Echo/RS485Echo.ino) This example makes echo. If you send some information to board it return it. It supports RS485.
- [RS485Input.ino](./examples/RS485Input/RS485Input.ino) The example reading isolated inputs and returning them statuses. It supports RS485.
- [RS485Relay.ino](./examples/RS485Relay/RS485Relay.ino) With this example you can manipulate the board relays via RS485.
- [TCPInputWE.ino](./examples/TCPInputWE/TCPInputWE.ino) Reading isolated inputs via TCP. It supports WiFi and Ethernet communication.
- [TCPRelayWE.ino](./examples/TCPRelayWE/TCPRelayWE.ino) With this example you can manipulate relays on the board via TCP. It supports WiFi and Ethernet communication.
- [UDPInputWE.ino](./examples/UDPInputWE/UDPInputWE.ino) Reading isolated inputs via UDP. It supports WiFi and Ethernet communication.
- [UDPRelayWE.ino](./examples/UDPRelayWE/UDPRelayWE.ino) With this example you can manipulate relays on the board via UDP. It supports WiFi and Ethernet communication.
- [Web1WireWE.ino](./examples/Web1WireWE/Web1WireWE.ino) A web example which reads and show temperature from DS18B20 sensor. It supports WiFi and Ethernet communication.
- [WebDHTWE.ino](./examples/WebDHTWE/WebDHTWE.ino) This web example which reads and show temperature and humidity from DHT22 sensor. It supports WiFi and Ethernet communication.
- [WebInputWE.ino](./examples/WebInputWE/WebInputWE.ino) Reading isolated inputs and show them statuses in web page. It supports WiFi and Ethernet communication.
- [WebRS485WE.ino](./examples/WebRS485WE/WebRS485WE.ino) In this example you can write text information in web page and send it via RS485. If opposite device respond with data. It can be shown in the web page. It supports WiFi and Ethernet (RS485) communication.
- [WebRelayWE.ino](./examples/WebRelayWE/WebRelayWE.ino) Manipulating the board relays via web page.  It supports WiFi and Ethernet (RS485) communication.