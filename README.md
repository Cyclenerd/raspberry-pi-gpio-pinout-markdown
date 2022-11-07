# Raspberry Pi Pinout

[![Bagde: Raspberry Pi](https://img.shields.io/badge/Raspberry%20Pi-C51A4A?logo=Raspberry-Pi)](#readme)

Raspberry Pi GPIO pinout:

<!--
  Markdown table with Raspberry Pi GPIO pinout
  https://github.com/Cyclenerd/raspberry-pi-gpio-pinout-markdown
-->
| #  |           | PIN  |    |    | PIN  |          | #  |
|----|-----------|------|----|----|------|----------|----|
| 1  | 3v3 Power | `1`  | 🟧 | 🔴 | `2`  | 5v Power | 20 |
| 2  | GPIO 2    | `3`  | 🔵 | 🔴 | `4`  | 5v Power | 19 |
| 3  | GPIO 3    | `5`  | 🔵 | ⚫ | `6`  | *Ground* | 18 |
| 4  | GPIO 4    | `7`  | 🟢 | 🟣 | `8`  | GPIO 14  | 17 |
| 5  | *Ground*  | `9`  | ⚫ | 🟣 | `10` | GPIO 15  | 16 |
| 6  | GPIO 17   | `11` | 🟢 | 🟤 | `12` | GPIO 18  | 15 |
| 7  | GPIO 27   | `13` | 🟢 | ⚫ | `14` | *Ground* | 14 |
| 8  | GPIO 22   | `15` | 🟢 | 🟢 | `16` | GPIO 23  | 13 |
| 9  | 3v3 Power | `17` | 🟠 | 🟢 | `18` | GPIO 24  | 12 |
| 10 | GPIO 10   | `19` | 🟡 | ⚫ | `20` | *Ground* | 11 |
| 11 | GPIO 9    | `21` | 🟡 | 🟢 | `22` | GPIO 25  | 10 |
| 12 | GPIO 11   | `23` | 🟡 | 🟡 | `24` | GPIO 8   | 9  |
| 13 | *Ground*  | `25` | ⚫ | 🟡 | `26` | GPIO 7   | 8  |
| 14 | GPIO 0    | `27` | 🔵 | 🔵 | `28` | GPIO 1   | 7  |
| 15 | GPIO 5    | `29` | 🟢 | ⚫ | `30` | *Ground* | 6  |
| 16 | GPIO 6    | `31` | 🟢 | 🟢 | `32` | GPIO 12  | 5  |
| 17 | GPIO 13   | `33` | 🟢 | ⚫ | `34` | *Ground* | 4  |
| 18 | GPIO 19   | `35` | 🟤 | 🟢 | `36` | GPIO 16  | 3  |
| 19 | GPIO 26   | `37` | 🟢 | 🟤 | `38` | GPIO 20  | 2  |
| 20 | *Ground*  | `39` | ⚫ | 🟤 | `40` | GPIO 21  | 1  |

**Legend:**

* 🟢 GPIO (General Purpose IO)
* 🟡 SPI (Serial Peripheral Interface)
* 🔵 I2C (Inter-integrated Circuit)
* 🟣 UART (Universal Asyncronous)
* 🟤 PCM (Pulse Code Modulation)
* ⚫ Ground
* 🔴 5v (Power)
* 🟠 3.3v (Power)

The number (#) on the left and right should help you count the pins.
This way you can find the pin you need faster.

Source: <https://pinout.xyz/>

## ❤️ Contributing

Have a patch that will benefit this project?
Awesome! Follow these steps to have it accepted.

1. Fork this Git repository and make your changes.
1. Create a Pull Request.
1. Incorporate review feedback to your changes.
1. Accepted!


## 📜 License

All files in this repository are under the [Apache License, Version 2.0](LICENSE) unless noted otherwise.

Please note: No warranty