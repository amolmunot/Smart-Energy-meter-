

#### **Smart Energy Meter with IoT Integration 🔋📡**  
A **real-time energy monitoring system** using **ESP32 and PIC16F877A**, designed to measure **voltage, current, and power consumption** while transmitting data to **Thingspeak via MQTT/Wi-Fi** for remote monitoring.  

---

## 📌 **Features**  
✅ **Accurate Energy Monitoring** – Measures **voltage (ZMPT101B)** & **current (ACS712)** with real-time power calculation.  
✅ **IoT Connectivity** – Sends data to **Thingspeak** using **ESP32 (Wi-Fi) and MQTT protocol**.  
✅ **Remote Dashboard** – Monitor energy consumption on a **web dashboard/mobile app**.  
✅ **Embedded C Firmware** – Optimized for **low latency, efficient data transmission, and system reliability**.  
✅ **LCD Display (Optional)** – Shows real-time values for local monitoring.  

---

## 🛠️ **Hardware Components**  
- **ESP32 / PIC16F877A** – Microcontrollers for IoT & data processing  
- **ZMPT101B** – Voltage sensor  
- **ACS712** – Current sensor  
- **Wi-Fi Module (ESP32)** – Sends data to the cloud  
- **16x2 LCD (Optional)** – Displays real-time energy values  
- **Relay Module (Optional)** – Automatic load control  

---

## 🖥️ **Software & Tools Used**  
- **Arduino IDE** – ESP32 firmware development  
- **MPLAB + XC8 Compiler** – PIC16F877A firmware  
- **Thingspeak** – Cloud IoT platform for real-time data visualization  
- **Xilinx Vivado (Optional)** – FPGA-based power optimization  

---

## 🚀 **How It Works?**  
1️⃣ **PIC16F877A reads voltage & current**, calculates power, and transmits data via **UART to ESP32**.  
2️⃣ **ESP32 receives the data, processes it, and sends it to Thingspeak** over MQTT.  
3️⃣ **Users can monitor power consumption remotely** via the Thingspeak dashboard.  
4️⃣ (Optional) **LCD display shows live energy data locally**.  

---

## 📂 **Repository Structure**  
```
/ Firmware
   ├── ESP32_Code.ino          # ESP32 Wi-Fi & Thingspeak integration
   ├── PIC16F877A_Code.c        # PIC firmware for sensor interfacing
/ Schematics
   ├── Circuit_Diagram.png      # Circuit wiring diagram
   ├── PCB_Layout.png           # PCB design layout
/ Docs
   ├── README.md                # Project Documentation
```

---

---

---

