# esp32-wol-panel
A smart touch panel built on ESP32-C6 with a 1.47" LCD that allows you to power on local network PCs via Wake-on-LAN, manage devices, and visualize boot states with animations.

## 🚀 Features

- Wake-on-LAN (WOL) for multiple PCs
- Touch UI with animations
- Wi-Fi provisioning via Access Point (Captive Portal)
- Add / remove / manage devices
- Persistent storage (NVS / SPIFFS / LittleFS)
- Boot status visualization (planned)
- Lightweight and responsive UI

## 📱 Hardware

- ESP32-C6
- 1.47" Touch LCD
- Wi-Fi connectivity

## 🧠 Use Case

Control and power on your home lab / PCs with a dedicated physical device.

## ⚙️ Planned Features

- Ping / status detection
- Custom device icons
- OTA updates
- Themes (dark/light)
- Integration with Home Assistant (optional)

## 🔌 How it works

1. Device starts in AP mode (first boot)
2. User connects and configures Wi-Fi
3. Devices (PCs) can be added via UI
4. Tap on device → sends Wake-on-LAN packet
5. UI shows animation and status

## 🛠 Tech Stack

- ESP-IDF / Arduino (TBD)
- LVGL for UI
- Async networking
- NVS / LittleFS for storage

## 📦 Project Structure (planned)
/src
/ui
/network
/storage
/wol
/main

## 📄 License
MIT
