# IoT-Based Farm Monitoring Simulation with AI Prediction

![Farm Monitoring System](pic.jpg)

## Project Overview:

This project simulates an IoT-based farm monitoring system using:

- **TinkerCAD** (for virtual sensor simulation)
- **Node-RED** (for data flow & dashboard)
- **Firebase** (for real-time cloud storage)
- **Google Colab & Machine Learning** (for AI-based crop health prediction)

---

## Technologies Used:

### Hardware (Simulated in TinkerCAD)
- **Soil Moisture Sensor** (Potentiometer)
- **Temperature & Humidity Sensor** (DHT11)
- **Light Sensor** (LDR)
- **Water Level Sensor** (Variable Resistor)
- **Arduino/ESP32**

### IoT Communication
- **Node-RED** (MQTT/HTTP)
- **Firebase** (Real-time database)

### AI/ML for Prediction
- **Google Colab & Python**

---

## Features of the System:

### Real-Time Monitoring:
- Sensors collect real-time data for **soil moisture**, **temperature & humidity**, **light levels**, and **water levels**.

### Cloud Integration:
- Data from the sensors are sent to **Firebase**, providing cloud storage for easy access and analysis.
  
### AI-Based Predictions:
- **Google Colab** and **Machine Learning** algorithms analyze historical data to make predictions about **crop health**, identifying potential problems (e.g., watering needs, pest detection, etc.).

### Data Flow and Dashboard:
- **Node-RED** integrates the data flow and provides an intuitive dashboard for visualizing the real-time sensor data and AI predictions.

---

## How It Works:

1. **Sensor Data Collection**: The sensors (moisture, temperature, humidity, light, water level) collect data from the farm environment.
2. **Data Transmission**: The data is transmitted to the cloud (Firebase) through **Node-RED** using MQTT or HTTP protocols.
3. **AI Prediction**: Using **Google Colab** and machine learning models, predictions about crop health and optimal farming actions (e.g., when to water, pest control) are made.
4. **Real-Time Visualization**: The dashboard created in **Node-RED** allows users to monitor the farm's real-time conditions and predictions.

---

## Benefits of the System:
- **Automated Farm Management**: Minimizes human intervention by predicting
