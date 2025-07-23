#MindVault - Parts List

|   Component                      |   Quantity    |  Status   |     Notes                                           |
|----------------------------------|---------------|-----------|-----------------------------------------------------|
| ESP32 DevKit                     |   1           |   ❌      | Main MCU with Wi-Fi, filesystem, and encryption     |
| LCD Display - For development    |   1           |   ✅      | LCD -  journaling UI already in Arduino kit         |
| OLED Display (128x64, I2C)       |   1           |   ❌      | SSD1306 0.96" — for journaling UI                   |
| Push Buttons                     |   3–5         |   ✅      | For input/navigation — already in Arduino kit       |
| WS2812 RGB LED / NeoPixel        |   1           |   ❌      | For mood color feedback                             |
| Breadboard                       |   1           |   ✅      | For building circuit — in Arduino kit               |
| Jumper Wires (Male–Male)         |   20+         |   ✅      | For connections — in Arduino kit                    |
| Resistors (10kΩ + 220Ω)          |   5+          |   ✅      | For pull-downs and LED current limiting             |
| Rotary Encoder (Optional)        |   1           |   ❌      | Alternative input if not using buttons              |
| MicroSD Card Module (Optional)   |   1           |   ❌      | To store large encrypted logs                       |
| USB Cable (for ESP32)            |   1           |   ✅      | For uploading code and powering device              |
| Battery / USB Power Supply       |   1           |   ❌      | Optional for portability phase                      |
| Buzzer (Optional)                |   1           |   ✅      | For sound feedback — in Arduino kit                 |
| Case / Enclosure (Optional)      |   1           |   ❌      | For final presentation — DIY or 3D printed          |


Must-haves to begin : 

1. ESP32 Devkit - Main microcontroller with Wi-Fi, AES Support, file system
2. LCD Display - To display the journal entries
3. Push Buttons
4. Breadboard
5. Jumper Wires
6. USB Cable
7. Resistors

Optional & Can wait :

1. WS2812 RGB LED / NeoPixel
2. MicroSD Card Module
3. Rotary Encoder
4. Battery / Case
