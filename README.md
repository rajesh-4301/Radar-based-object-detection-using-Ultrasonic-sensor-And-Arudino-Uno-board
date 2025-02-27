# Radar-based-object-detection-using-Ultrasonic-sensor-And-Arudino-Uno-board


## **Project Description**  
This project simulates a **radar system** using an **Ultrasonic Sensor (HC-SR04)** and an **Arduino Uno**. The system detects obstacles by emitting ultrasonic waves and analyzing their reflection. A **servo motor** rotates the ultrasonic sensor, allowing it to scan the surroundings. The detected object distances are displayed in real time using the **Processing IDE** or the **Serial Monitor**.  

## **Features**  
✔️ Object detection using **HC-SR04 Ultrasonic Sensor**  
✔️ **Rotating servo motor** for scanning the environment  
✔️ **Real-time visualization** using Processing IDE  
✔️ **Distance measurement** displayed in serial monitor  
✔️ **Alert system** (Optional: Buzzer for nearby objects)  

## **Components Required**  
- **Arduino Uno**  
- **HC-SR04 Ultrasonic Sensor**  
- **SG90 Servo Motor**  
- **Jumper Wires**  
- **Breadboard**  
- (Optional) **Buzzer or LED for alerts**  

## **Circuit Diagram**  
🔹 **HC-SR04 Connections:**  
- VCC → 5V  
- GND → GND  
- Trig → Arduino Digital Pin 9  
- Echo → Arduino Digital Pin 10  

🔹 **Servo Motor Connections:**  
- VCC → 5V  
- GND → GND  
- Signal → Arduino Digital Pin 6  

## **Installation & Setup**  
1. **Connect the components** as per the circuit diagram.  
2. **Upload the Arduino code** to the Arduino Uno using the Arduino IDE.  
3. **Install Processing IDE** (if using for visualization).  
4. **Run the Processing script** to visualize radar-like scanning.  
5. **Observe the detected objects** on the Processing display or Serial Monitor.  



## **Visualization (Processing IDE)**  
To visualize the radar output, use a **Processing** script that reads data from the **Serial Monitor** and displays it graphically.

## **Applications**  
✅ Obstacle detection for robotics  
✅ Smart parking systems  
✅ Collision avoidance systems  
✅ Security and surveillance  

## **Future Enhancements**  
🚀 Use **multiple sensors** for enhanced coverage  
🚀 Implement **Wi-Fi or Bluetooth** for remote monitoring  
🚀 Add a **buzzer alert system** for close-range detection  


