# Smart Library IoT System

An IoT-based Smart Library Management System using ESP32 and RFID technology.

## Features

- Student authentication using RFID card
- Book issuing using RFID tags
- LCD display notifications
- ESP32-based hardware system

## Components Used

- ESP32
- MFRC522 RFID Reader
- RFID Tags
- 16x2 I2C LCD
- Breadboard
- Jumper Wires

## Working

1. Student scans RFID card
2. ESP32 verifies user
3. Student scans book RFID tag
4. Book gets issued
5. LCD displays issue confirmation and due date

## Circuit Connections

### RFID Connections

| RFID | ESP32 |
|------|--------|
| SDA | 5 |
| SCK | 18 |
| MOSI | 23 |
| MISO | 19 |
| RST | 22 |
| GND | GND |
| 3.3V | 3.3V |

### LCD Connections

| LCD | ESP32 |
|-----|--------|
| SDA | 21 |
| SCL | 22 |


## Future Improvements

- Web dashboard
- Cloud database
- Mobile app integration
- Fine calculation
- Online notifications

## Author

Varsha Reddy
