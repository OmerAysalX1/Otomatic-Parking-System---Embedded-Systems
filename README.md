
# 🚗 Automatic Parking System

This project is an automatic parking system developed using Raspberry Pi Pico. The system can show the number of empty spaces in the parking area, automatically open the door for vehicles entering, and indicate the occupancy status of the parking area with LED lights.

## ⚙️ Features
- **Automatic Door Opening:** The door is automatically opened using a servo motor for vehicles approaching the door.
- **LED Indicator:**
- Green LED: Parking space is available.
- Blue LED: One parking space left.
- Red LED: Parking space is full.
- **Audio Warning:** Buzzer with audio warning for each vehicle entrance.
- **LCD Screen:** Shows the number of available spaces in the parking area.
- **Manual Reset:** The system is reset with the button and the parking counter is reset.
- **Potentiometer Control:** RGB LED and additional red LED brightness can be adjusted with the potentiometer.

## 🔩 Materials Used
- Raspberry Pi Pico WH
- RGB LED and Red LED
- Servo Motor
- 16x2 LCD Screen
- Buzzer
- Ultrasonic Distance Sensor
- Button
- 2x Potentiometer

## 🛠️ Circuit Diagram
You can take a look at the Fritzing diagram below for the circuit diagram of the project:

![Circuit Diagram](![WhatsApp Image 2025-02-08 at 18 33 09](https://github.com/user-attachments/assets/5b3ffa3c-ab99-4e53-8bf5-9b979f7f8d6d)
)

## 🚀 Installation
1. Make the necessary connections and install the circuit.
2. Upload the codes to Raspberry Pi Pico.
3. Start the system and control the parking area.

## 🎮 Usage
- Approach your car to the door, the door will open automatically.
- The number of parking spaces will decrease after entering.
- When the parking area is full, the red LED turns on and the extra red LED is active.
- Press the button to reset the system.

## 📹 Demo
Click to watch the project working video:


https://github.com/user-attachments/assets/ea865a05-38a4-42a0-a4f0-27d90ff4b372






## 🖼️ Screenshots
![Green LED - Parking Area Available](![WhatsApp Image 2025-02-08 at 18 20 15](https://github.com/user-attachments/assets/568928bf-576d-43a2-990a-d63d6aa8be5b)
)
![Blue LED - One Parking Space Left](![WhatsApp Image 2025-02-08 at 18 20 19](https://github.com/user-attachments/assets/4c9b7278-10f2-49b2-add8-5690de35cb8e)
)
![Red LED - Parking Area Full](![WhatsApp Image 2025-02-08 at 18 20 20](https://github.com/user-attachments/assets/c78f2187-1938-4f01-9296-2f596b715c5e)
)
