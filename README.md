
# Smart Dustbin with Arduino UNO and RFID-Based Reward System

🚮 Designed and prototyped a smart dustbin integrating **ultrasonic**, **soil moisture**, and **RFID** sensors using Arduino UNO for waste management and citizen reward tracking.

---

## 🔧 Components Used

- Arduino UNO
- Ultrasonic Sensor (HC-SR04)
- Soil Moisture Sensor
- Servo Motor
- RFID Reader (RC522)
- RFID Tags
- Buzzer
- Jumper Wires
- Breadboard
- LCD Display (optional)

---

## 💡 Features

- **Touchless Waste Disposal**: Uses ultrasonic sensor to open lid automatically.
- **Moisture Detection**: Soil moisture sensor checks if waste is wet or dry.
- **RFID Reward System**:
  - Each person uses their **RFID tag** to identify themselves.
  - When valid waste is disposed, points/rewards are **added to their profile**.
  - These rewards can later be **redeemed for gifts or coupons** via an external system or mobile app.

---

## 📈 How It Works

1. User scans their **RFID card**.
2. If valid, the lid opens automatically.
3. The system logs the disposal and awards points.
4. Data can be sent to a central server or stored locally.

---

## 💡 Future Enhancements

- Connect to IoT platform (e.g., Firebase or Thingspeak).
- Add a mobile app to track and redeem rewards.
- Implement automatic waste segregation using color sensors.
- Solar-powered battery for sustainable operation.

---

## 📁 Project Files

- `smart_dustbin.ino` - Arduino source code.
- `circuit_diagram.png` - Circuit layout for connection.
- `README.md` - This documentation file.

---

## 🤝 Credits

Developed by: *GAYATHIRI_B*  
For: Hackathon

---

