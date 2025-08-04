# ESP32-S3 HAT V2

[![Board Animation](board_animation.gif)](pi_rec.mp4)

A compact and powerful development board based on the Espressif **ESP32-S3-WROOM-1** module. Designed in a standard HAT form factor, it's perfect for a wide range of IoT projects, from home automation to prototyping complex wireless applications.

***

## ✨ Features

* **Powerful Core**: Features the **ESP32-S3-WROOM-1** module with a dual-core Xtensa® LX7 MCU.
* **Wireless Connectivity**: Integrated 2.4 GHz Wi-Fi ($802.11 \text{ b/g/n}$) and Bluetooth 5 (LE).
* **Modern Interface**: Uses a **USB-C** connector for power, programming, and native USB OTG functionality.
* **Standard Form Factor**: Designed as a HAT, making it easy to integrate with systems like a Raspberry Pi or to use as a standalone board.
* **User I/O**: Includes on-board LEDs and reset/boot buttons for easy interaction and development.
* **Extensible**: Provides access to ESP32-S3 GPIO pins through standard headers for connecting sensors, displays, and other peripherals.

***

## 🛠️ Technical Specifications

| Specification      | Details                                          |
| ------------------ | ------------------------------------------------ |
| **Microcontroller**| Espressif ESP32-S3-WROOM-1                         |
| **CPU** | Dual-core Xtensa® LX7 @ up to 240 MHz            |
| **Wireless** | 2.4 GHz Wi-Fi & Bluetooth 5 (LE)                 |
| **Power Input** | 5V via USB-C                                     |
| **Logic Level** | 3.3V                                             |
| **PCB Dimensions** | Conforms to standard HAT size (Approx. 65mm x 56mm) |

***

## 📂 Repository Contents

This repository contains all the necessary files to manufacture and assemble the board.

* `BOM/`: Contains the Bill of Materials (`.csv`) listing all required components.
* `GERBER/`: Gerber and drill files needed for PCB manufacturing.
* `3d/`: 3D models for the PCB and its components, useful for mechanical integration.
* `*.kicad_*`: The original KiCad v7 project files, including the schematic, PCB layout, and project configuration.
* `pi_rec.mp4`: The source video animation of the board.
* `board_animation.gif`: The animated GIF preview of the board.

***

## 🚀 Getting Started (Manufacturing Guide)

To create your own ESP32-S3 HAT V2, follow these steps:

1.  **Download the Gerbers**: Clone this repository or download the contents of the `/GERBER/` directory as a single ZIP file.
2.  **Order the PCB**: Upload the ZIP file to a PCB manufacturer of your choice (e.g., JLCPCB, PCBWay, OSH Park) and place your order.
3.  **Source Components**: Use the Bill of Materials file located in the `/BOM/` directory to order all necessary electronic components from a distributor like Digi-Key, Mouser, or LCSC.
4.  **Assemble the Board**: Solder the components onto the PCB. You can use the schematic, PCB layout files, and the board preview image as a reference for component placement.

***

## 📄 License

This is an open-source hardware project. Consider adding a license file (e.g., [CERN-OHL-P-2.0](https://spdx.org/licenses/CERN-OHL-P-2.0.html) or [MIT](https://opensource.org/licenses/MIT)) to define the permissions and limitations for users.
