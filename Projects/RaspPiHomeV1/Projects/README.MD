# 🧠 Programming Microcontrollers with Raspberry Pi 4B - RaspPiHomeV1

This document outlines how the **Raspberry Pi 4 Model B** can be used as a powerful, portable workstation for programming microcontrollers (MCUs) such as the Raspberry Pi Pico using **CircuitPython**.

![RaspPiHomeV1 Setup](https://github.com/jhherre3/Raspberrypi4b/blob/main/Files/ProgrammingwithRPiHome.png)

---

## 🛠️ Hardware Setup

- **Raspberry Pi 4B** (4GB or 8GB recommended)
- **Raspberry Pi Pico** (or other CircuitPython-compatible MCU)
- **Mini HDMI Touchscreen Display**
- **iPazzPort Wireless Keyboard with Touchpad**
- **USB cable (Micro USB for Pico)**
- **Power supply for Pi (at least 3A)**

> ✅ Optional: Custom 3D printed or fabricated case to house display and Pi for a portable dev station

---

## 🧪 Software & Tools

- [Thonny IDE](https://thonny.org/) — For flashing CircuitPython and quick code tests
- [Visual Studio Code](https://code.visualstudio.com/) — For advanced editing
- CircuitPython firmware for the target MCU
- Git for version control
- Optional: `rsync` or `ampy` for file management

---

## 🔌 Getting Started

### 1. Put Your MCU in Boot Mode

- Hold down the **BOOTSEL** button on the Raspberry Pi Pico.
- While holding it, connect the Pico to your Raspberry Pi 4B via USB.
- A new volume called `RPI-RP2` will appear on your desktop.

### 2. Flash CircuitPython Using Thonny

- Open **Thonny IDE** on your Raspberry Pi 4B.
- In the **bottom right corner**, click the interpreter dropdown.
- Select **CircuitPython (generic)**.
- Thonny will detect the board and automatically flash the correct CircuitPython firmware.
- Once done, the board will reboot and appear as `CIRCUITPY`.

### 3. Open and Edit with Visual Studio Code

- Launch **Visual Studio Code**.
- Open the `CIRCUITPY` USB device as a folder.
- Edit or create your `code.py` and other files inside.
- Any changes will run automatically on the microcontroller after saving.

