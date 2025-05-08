# 🖥️ Raspberry Pi 4B Smart Kiosk Tablet

This is a custom-built **desktop tablet and kiosk** powered by a Raspberry Pi 4 Model B.  
Inspired by smart hubs like the Google Nest Hub and Alexa Show, this device combines entertainment, utility, and interactivity in one sleek build.

---

## 📸 Project Overview

![Smart Kiosk Tablet Side View](https://raw.githubusercontent.com/jhherre3/Raspberrypi4b/main/Files/ripihomev1side.jpg)



This project transforms the Raspberry Pi 4B into a **touchscreen smart kiosk** with:
- Dual **onboard speakers**
- RetroPie support for gaming 🎮
- USB, HDMI, and power **accessible ports**
- A 7-inch IPS **touch display**
- Desktop/tablet form factor for use as a smart clock, assistant, arcade, or media hub

---

## 🧩 Features

- 🖼️ **Capacitive Touchscreen Display** (7-inch IPS, HDMI)
- 🔊 **Built-in Stereo Speakers** (left/right channels via onboard amp)
- 🕹️ **RetroPie Emulation Station**
- 🔌 **Exposed Ports** (USB, HDMI, 3.5mm, Power)
- 🔁 Designed for daily use on a desk or as a wall-mounted interface
- 🔧 Fully customizable frontend (clock, weather, YouTube, terminal, etc.)

---

## 🧰 Components Used

| Component                | Details                                     |
|--------------------------|---------------------------------------------|
| Raspberry Pi 4B          | 4GB RAM version                             |
| 7-inch HDMI Touchscreen  | 1024×600 IPS with USB touch support         |
| APA2063 Amplifier IC     | Drives 4Ω–8Ω speakers with 2.6W per channel |
| Dual 8Ω 2W Speakers       | Mounted inside the enclosure                |
| Custom Enclosure         | Designed for desktop or wall placement      |
| RetroPie                 | Installed for classic arcade gaming         |

---

## 🖼️ Gallery

![Smart Kiosk Tablet Side View](https://github.com/jhherre3/Raspberrypi4b/blob/main/Files/Rpiassemble.png)

---

## 🔊 Speaker & Audio Notes

- Speakers are powered via a **2.6W/channel PA circuit** (APA2063)
- Audio can be sourced from:
  - 3.5mm jack (analog)
  - HDMI splitter 2.0mm JST (digital)
- Ideal speakers: **8Ω 2W** mini drivers

---

## 📌 Tips

- You can also power this with a **5V 3A USB-C adapter**
- Add a **heat sink or fan** if running RetroPie or intensive apps
- For wall mounting, consider VESA-compatible holes in your enclosure

---

## 🆕 Version 2 – Concept and Future Add-ons

![Smart Kiosk Tablet Side View](https://github.com/jhherre3/Raspberrypi4b/blob/main/Files/RaspPiHomeV2.png)

### 🔧 **Smart Kiosk Tablet – V2 Roadmap**

Version 2 of the Smart Kiosk Tablet builds on the original concept with enhancements in design, modularity, and functionality. The goal is to make the device more versatile for various use cases, including home automation, desk productivity, gaming, and entertainment.

---

### ✨ Planned V2 Enhancements

| Upgrade Area       | Planned Improvements                                                                 |
|--------------------|--------------------------------------------------------------------------------------|
| 📺 Display          | Larger 7–10" IPS screen, better touch response, ambient light sensor support        |
| 🔊 Audio            | Higher quality speakers, stereo separation, headphone jack, volume control knob    |
| 🧠 Performance      | Raspberry Pi 5 support (if needed), better thermal handling, fan mount              |
| 🧲 Mounting         | Magnetic or VESA-compatible rear for wall/monitor arm mounting                      |
| 🔌 Port Access      | Reoriented ports for easier cable management                                        |
| 🎮 Input            | Front joystick or gamepad support for RetroPie or emulator menu navigation          |
| 🌐 Networking       | Optional external antenna for improved Wi-Fi or built-in Ethernet breakout          |
| ⚡ Power Options    | USB-C + barrel jack input, battery power with charge circuit (optional UPS module) |

---

### 🧩 Add-On & Expansion Ideas

- **Camera Module (Pi Cam)**: For face detection, video calls, or surveillance
- **Microphone Array**: Enable voice assistant functionality (offline or Google Assistant integration)
- **Ambient Display Mode**: Show time, calendar, weather, RSS feeds, and system info
- **Home Assistant Dashboard**: Integrate with Home Assistant or similar via browser
- **IR Receiver**: For media center remote control
- **Rotating Base Add-on**: Servo-powered base for directional face tracking or room scanning
- **GPIO Expansion Board**: For prototyping, automation, or custom HATs

---

### 📦 Modular Case Design (V2)

V2 will feature a sleeker and modular case that allows:
- Removable back panel for upgrades
- Internal compartments for amp, Pi, and wiring
- Mount points for accessories like cameras or cooling fans
- Easy front bezel swap for screen upgrades

---

> Want to contribute an idea or feature? Open a GitHub issue or pull request with your V2 suggestions!


