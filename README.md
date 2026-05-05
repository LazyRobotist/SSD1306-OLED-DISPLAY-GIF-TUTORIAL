<img width="4096" height="2304" alt="1778000606169" src="https://github.com/user-attachments/assets/4814ff8b-15c9-4ac0-8057-a8c70cc300e8" />


# SSD1306-OLED-DISPLAY-GIF-TUTORIAL

A tutorial on how to display any GIF or video on a 
SSD1306 OLED Display using a XIAO ESP32-S3 (or any 
ESP32/Arduino). Includes full code for the viral 
Low Cortisol Dance and Bad Apple (partial) demos.

## What You Need
- Seeed Studio XIAO ESP32-S3 (or any ESP32/Arduino)
- SSD1306 0.96" OLED Display (128x64)
- Jumper wires

## Wiring
| OLED | XIAO ESP32-S3 |
|------|--------------|
| VCC  | 3.3V         |
| GND  | GND          |
| SDA  | D4           |
| SCL  | D5           |

## Libraries Required
Install these from Arduino IDE Library Manager:
- Adafruit SSD1306
- Adafruit GFX

## How To Convert Your Own GIF (Tutorial soon...)
1. Cut your clip → ezgif.com (resize to 128x64)
2. Convert to GIF → ezgif.com
3. GIF to byte array → image2cpp (javl.github.io/image2cpp)
4. Paste output into the Base Code file
5. Upload and done!

## Files
- **Base Code** → Template code, paste your frames here
- **Low Cortisol - Agnes Tachyon** → Full working example
- **Bad Apple (partial)** → 735 frames, 50000+ lines

## Credits
Made by Lazy Robotist
