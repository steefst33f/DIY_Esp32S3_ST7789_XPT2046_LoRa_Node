# DIY 320x240 TFT stand alone Lora Node 
DIY Esp32S3 ST7789 XPT2046 Lora Node

This is a DIY stand alone Lora node with a 320x240 TFT Display with resistive touch, GPS and Keyboard
Its made to be able to cheaply play/develop with the experimental Meshtastic UI

Its is made out of the following components:
- ESP32S3 N16R8 Devkit-C-1 Clone
- TFT Display (320x240) ST7789 driver
- Resistive touch XPT2046 driver
- Lora Sx1262 (WaveShare)
- GNNS NEO-6M (Blox)
- keyboard M5CardKB (M5Stack)

### Connecting the components:
 <br>

| TFT ST7789 | ESP32S3 |
| :--- | :---|
| SDO (MISO) | GPIO 13 |
| LED | GPIO 7 |
| SCK | GPIO 12 |
| SDI (MOSI) | GPIO 11 |
| DC | GPIO 6 |
| RST | GPIO 5 |
| CS | GPIO 10 |
| GND | GND |
| VCC | 3V3 |

 <br>

| Touch XPT2046 | ESP32S3 |
| :--- | :---|
| T_IRQ | GPIO 4 |
| T_DO (MISO) | GPIO 13 |
| T_DIN (MOSI) | GPIO 11 |
| T_CS | GPIO 14 |
| T_CLK | GPIO 12 |

 <br>

| SX1262 | ESP32S3 |
| :--- | :---|
| ANT | - |
| GND | - |
| CS | GPIO 16 |
| CLK | GPIO 12 |
| MOSI | GPIO 11 |
| MISO | GPIO 13 |
| RESET | GPIO 15 |
| BUSY | GPIO 18 | 
| GND | - |
| GND | - |
| RXEN | - |
| TXEN | - |
| DIO2 | - |
| DIO1 (IRQ) | GPIO 41 |
| GND | GND |
| 3V3 | 3V3 |

 <br>

| GNNS GY-NEO-6MV2 | ESP32S3 |
| :--- | :---|
| VCC | 3V3 |
| RX | GPIO 2 |
| TX | GPIO 1 |
| GND | GND |

 <br>

|cardKB | ESP32S3 |
| :--- | :---|
| VCC | 3V3 |
| GND | GND |
| SDA | GPIO 8 |
| SCL | GPIO 9 |
￼
### Which can be connected with dupont cables like this:

![Image of DIY ESP32S3 ST7789 XPT2046 LoRa Node](DIYLoraNode.png)	
