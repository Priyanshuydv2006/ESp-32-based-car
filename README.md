# 🚗 ESP32 Bluetooth Controlled RC Car

A Bluetooth-controlled RC car built using the ESP32 microcontroller and BTS7960 high-current motor driver. The vehicle can be wirelessly controlled using a smartphone over Bluetooth, providing smooth forward, reverse, left, right, and stop operations.

---

## 📌 Features

- 📱 Bluetooth control using Android smartphone
- ⚡ ESP32-based controller
- 🔋 High-power BTS7960 motor driver
- 🎮 Real-time directional control
- 🔄 Forward, Reverse, Left, Right & Stop
- 🚀 Fast response with low communication latency
- 🛠 Easy to modify and expand

---

## 🛠 Hardware Used

| Component | Quantity |
|-----------|----------|
| ESP32 Development Board | 1 |
| BTS7960 Motor Driver | 2|
| DC Gear Motors | 4 |
| RC Car Chassis | 1 |
| Wheels | 4 |
| Battery Pack | 1 |
| Connecting Wires | As Required |


---

## 💻 Software Used

- Arduino IDE
- ESP32 Board Package
- C++
- Bluetooth Serial Library

---

## ⚙️ Working Principle

1. The smartphone sends commands through Bluetooth.
2. ESP32 receives the command.
3. The command is processed in the program.
4. ESP32 generates control signals.
5. BTS7960 drives the motors according to the received command.
6. The car performs the requested movement.

---

## 📱 Control Commands

| Command | Action |
|---------|--------|
| F | Forward |
| B | Reverse |
| L | Left |
| R | Right |
| S | Stop |

---


## 🔌 Circuit Diagram

> (images/circuit_1.png)

```
ESP32 -------- BTS7960 -------- Motors
      \            |
       \           |
        Bluetooth Smartphone
```

---

## 🚀 Getting Started

1. Clone this repository

```
git clone https://github.com/Priyanshuydv2006/ESp-32-based-car
```

2. Open the project in Arduino IDE.

3. Install the ESP32 Board Package.

4. Select the correct COM Port.

5. Upload the code.

6. Pair your phone with the ESP32 Bluetooth device.

7. Open the Bluetooth Controller App and enjoy driving!

---

## 📷 Project Images

| Front | Working |
|-------|---------|
| *(Add Image)* | *(Add Image)* |

---

## 🎥 Demo


Example:

https:

---

## 🔮 Future Improvements

- Obstacle Avoidance
- Camera Streaming
- Wi-Fi Control
- GPS Navigation
- Voice Control
- Autonomous Mode

---

## 👨‍💻 Author

**Priyanshu Yadav**

Electrical and Computer Engineering (EACE)

Madhav Institute of Technology & Science (MITS), Gwalior

---

## ⭐ If you like this project

Give this repository a ⭐ on GitHub.
