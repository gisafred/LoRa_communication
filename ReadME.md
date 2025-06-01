# LoRa Communication Project

This project demonstrates simple point-to-point communication using LoRa modules (RFM95) with Arduino-compatible boards.

## Project Description

The repository contains two nearly identical sketches:
- A receiver that listens for incoming LoRa messages and sends acknowledgments
- A transmitter that sends messages and listens for replies

## Hardware Requirements

- 2x Adafruit Feather M0 with RFM95 LoRa module (or compatible boards)
- Antennas for both modules
- USB cables for programming and power

## Setup Instructions

1. Clone this repository
2. Upload the receiver code to one Feather board
3. Upload the transmitter code to another Feather board
4. Ensure both boards are powered and have antennas attached
5. Open serial monitors for both boards (115200 baud) to view communication

## Configuration parameters

Key configuration parameters:
- `RF95_FREQ`: Set to 915.0 MHz (adjust for your region)
- Pin assignments for your specific board
- Transmission power (5-23 dBm)

## Future Improvements

- Add message addressing for multiple nodes
- Implement error checking
- Include sensor data examples

## License

MIT License - See LICENSE file

team members: IRASUBIZA SALY NELSON,GISA FRED,HIMBAZA PARADIE EMMANUELA,ASINGIZWE BENITE,KWIZERA ALBERT, MARIE CYNTIA
