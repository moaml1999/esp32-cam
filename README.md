# Operate Esp32 cam by arduino board

# ESP32-CAM Pinout Diagram
<p> The following figure shows the ESP32-CAM pinout (AI-Thinker module).

![Esp32_cam_pinout](https://github.com/moaml1999/esp32-cam/blob/main/esp32_cam_pinout.jpg)

 </p> 
 

# Circuit Diagram to interface ESP32CAM with Arduino UNO
<p> Connect the ESP32-CAM board to your computer using an Arduino board. Follow the next schematic diagram:
  
![Esp32_cam_schematic_diagram](https://github.com/moaml1999/esp32-cam/blob/main/esp32_cam_arduino.jpeg) </p>
 
| ESP32-CAM | Arduino board |
| --- | --- |
| GND | GND |
| 5V | VCC |
| U0R | RX |
| U0T | TX |
  
  
## Installing the Esp32 Library & determine board : 
 
- Install the Esp32 library by going to “Tools > Board > Boards Manager > Search for Esp32 > Install Esp32 from Espressif Systems”.
- Select the right board: “Tools > Board > ESP32 Arduino > AI Thinker ESP32-CAM”.

![Esp32_cam_schematic_diagram](https://github.com/moaml1999/esp32-cam/blob/main/esp32_cam_arduino_connection.jpg)

