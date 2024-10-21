# Mini-Project

**Plantopia Spectra** is an IoT-based smart plant monitoring and automated watering system designed to enhance the precision and efficiency of plant care. By using sensors like soil moisture, temperature, and humidity sensors, the system monitors plant health in real-time and automates the watering process using a water pump, all managed via NodeMCU and cloud integration. The project encourages sustainable agricultural practices by optimizing water usage and minimizing resource wastage.

## Features
- **Real-Time Monitoring**: Tracks soil moisture, temperature, and humidity in real time.
- **Automated Watering**: Intelligent water pump activation based on soil moisture levels.
- **Remote Control**: Monitor and control the system via the Blynk app from anywhere.
- **Energy Efficient**: Uses power-efficient components with sleep mode support.
- **User-Friendly Interface**: LCD display for system status and mobile app integration for remote control.
- **Sustainable and Scalable**: Promotes efficient resource usage and supports system expansion for larger setups.

## Components
- **NodeMCU (ESP8266)**: Central control unit for connecting sensors, Wi-Fi, and cloud communication.
- **Soil Moisture Sensor**: Measures soil moisture to determine watering needs.
- **DHT11 Sensor**: Monitors temperature and humidity for optimal environmental conditions.
- **Relay Module**: Controls the water pump based on data from the sensors.
- **Water Pump**: Delivers water to plants when triggered by the system.
- **I2C LCD Display**: Displays sensor readings and system status.
- **Blynk App**: Provides a remote user interface for monitoring and controlling the system.

## Installation

### Hardware Setup
1. Connect the **NodeMCU (ESP8266)** to the sensors:
   - Soil moisture sensor to analog pin (A0).
   - DHT11 sensor to digital pins.
   - Relay module to control the water pump.
   - I2C LCD for display.
2. Connect the water pump to the relay module.
3. Ensure all components are powered using a stable 5V power supply.

### Software Setup
1. Install the **Arduino IDE** and add the **ESP8266 board** by following the instructions [here](https://arduino-esp8266.readthedocs.io/en/latest/installing.html).
2. Install the required libraries:
   - `DHT` library for the DHT11 sensor.
   - `Blynk` library for mobile control.
   - `LiquidCrystal_I2C` for the I2C LCD display.

3. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/plantopia-spectra.git

[Watch the demo on Vimeo](https://vimeo.com/1021869428?share=copy#t=0)

