# 🪨✋✂️ Rock Paper Scissors Gesture Combat Game Robot

## 📅 IoT & Embedded Systems Group Project

## 📌 Project Overview

The Rock Paper Scissors Gesture Combat Game Robot is an interactive human–robot gaming system that combines Arduino-based hardware with AI-powered hand gesture recognition. Players can challenge a robotic arm in the classic Rock–Paper–Scissors game using real-time hand gestures detected through a webcam.

When a player's hand is detected near the ultrasonic sensor, the game starts automatically. The webcam identifies the player's gesture (Rock ✊, Paper ✋, or Scissors ✌️), while the Arduino controls servo motors to perform the robot's move. The web application displays both gestures, determines the game result, and updates scores instantly.

---

## 🎯 Objectives

* Develop an interactive gesture-controlled gaming experience.
* Integrate hardware and software components in a real-time system.
* Implement AI-based hand gesture recognition.
* Create a fun and engaging human–robot interaction platform.

---

## 🧩 Key Features

✅ Real-time hand gesture detection using a webcam

✅ Automatic game start using ultrasonic sensor detection

✅ Servo motor-controlled robotic hand movements

✅ Random robot gesture generation

✅ Automatic Win / Lose / Draw decision logic

✅ Live score tracking system

✅ Real-time web interface synchronization

✅ Audio feedback using buzzer

---

## ⚙️ Technologies Used

### Hardware

* Arduino Nano
* HC-SR04 Ultrasonic Sensor
* Servo Motors (x3)
* Buzzer
* USB Webcam

### Software

* HTML5
* CSS3
* JavaScript
* React.js
* Vite
* Tailwind CSS
* Node.js
* TensorFlow.js / MediaPipe
* Arduino IDE

---

## 🪛 Hardware Configuration

| Component                | Pin |
| ------------------------ | --- |
| Ultrasonic Trigger       | A1  |
| Ultrasonic Echo          | A0  |
| Servo Motor 1 (Rock)     | A3  |
| Servo Motor 2 (Paper)    | A4  |
| Servo Motor 3 (Scissors) | A5  |
| Buzzer                   | D2  |

---

## 🔄 System Workflow

1. Player places their hand near the ultrasonic sensor.
2. Sensor detects the hand and starts the game.
3. Webcam captures the player's hand gesture.
4. AI model identifies Rock, Paper, or Scissors.
5. Arduino randomly selects and performs the robot gesture using servo motors.
6. Web application displays:

   * Player Gesture
   * Robot Gesture
   * Game Result
7. System determines:

   * Win 🏆
   * Lose ❌
   * Draw 🤝
8. Scores are updated automatically.

---

## 💻 How to Run the Project

### 🔸 Arduino Setup

1. Open `Arduino/rps_main.ino` using Arduino IDE.
2. Connect the Arduino Nano to your computer.
3. Upload the code to the board.
4. Connect all servos, ultrasonic sensor, and buzzer according to the circuit diagram.

### 🔸 Web Application Setup

#### Requirements

* Node.js
* npm

#### Installation

```bash
npm install
```

#### Run the Project

```bash
npm run dev
```

Open the local development URL displayed in the terminal.

---

## 📂 Project Structure

```text
rock-paper-scissors-gesture-combat-game/

│
├── Arduino/                 # Arduino source code
├── public/                  # Static assets
├── src/                     # React application source files
├── index.html               # Main webpage
├── package.json             # Project dependencies
├── vite.config.ts           # Vite configuration
└── README.md                # Project documentation
```

---

## 📷 Project Images
<img width="1367" height="2048" alt="2025_11_03_23_40_IMG_4195" src="https://github.com/user-attachments/assets/6ecac5ce-6927-48c2-b693-dd283c7c8eaf" />
<img width="3024" height="4032" alt="2025_11_03_13_38_IMG_4057" src="https://github.com/user-attachments/assets/9c9ef7d5-9176-4efb-8735-ad9d870c9012" />


---

## 🚀 Future Improvements

* Multiplayer game mode
* Voice command support
* Mobile application integration
* AI difficulty levels
* Enhanced robotic hand design
* Online score leaderboard

---

## 👩‍💻 Development Team

**HNDSE 25.1 Batch**

* Mihili
* Thamasha
* Gothami

---

## 📜 License

This project is licensed under the MIT License and is available for educational and non-commercial use.


