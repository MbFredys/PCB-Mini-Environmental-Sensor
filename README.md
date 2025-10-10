# PCB-Mini-Environmental-Sensor
This is a compact environmental monitoring PCB design that enables precise tracking of multiple atmospheric parameters with the following features:

1. 🌡️ Monitors temperature, humidity, and atmospheric pressure using BME280 sensor
2. 💨 Measures air quality and CO2 equivalent with Sensirion SPG40 sensor
3. 📶 WiFi and Bluetooth connectivity via ESP32-C3-VROOM-02 microcontroller
4. 🔋 Battery-powered operation with 3.7V Li-ion battery and USB-C charging
5. ⚡ Efficient power management using TPS62203 step-down converter
6. 🔄 Automatic data logging with cloud connectivity capabilities
7. 💤 Ultra-low power consumption with deep sleep mode
8. 🌧️ Weather-resistant design suitable for indoor and outdoor use

# Usage
To use the environmental sensor node, follow these steps:

  1. Power the device using either the 3.7V battery or USB-C connection
  2. Place the sensor in your desired monitoring location (indoor or outdoor)
  3. Connect to WiFi using the device's configuration interface
  4. Monitor environmental data in real-time through the web dashboard
  5. Analyze historical trends
  6. Receive alerts when environmental parameters exceed safe levels

The device automatically optimizes power consumption by entering deep sleep between measurements, ensuring extended battery life while providing continuous environmental monitoring for smart home, agricultural, and industrial applications.

# Getting Started
To get started with the Environmental Sensor Node PCB design, follow these steps:

  1. Clone this repository to your local machine
  2. Open the PCB design files in your preferred EDA software (KiCAD recommended)
  3. Review the schematic and layout - pay special attention to:
  4. RF antenna keep-out zone for ESP32-C3
  5. I2C routing between sensors and microcontroller
  6. Power distribution network
  7. Send the files to PCBWay for professional fabrication

# Hardware Setup
After receiving your PCBs, solder components in this recommended order:

  1. Power section (TPS62203, MCP73831)
  2. ESP32-C3 module
  3. Sensors (BME280, SPG40)
  4. Passive components and connectors
  5. Program the ESP32-C3 via USB-C connection
  6. Connect a 3.7V Li-ion battery to the battery connector
  7. Test each sensor

# Contributing
If you would like to contribute to the Environmental Sensor Node project, please follow these steps:

  1. Fork this repository
  2. Create a feature branch (git checkout -b feature/improvement)
  3. Make your enhancements - consider:
  4. Power optimization techniques
  5. Additional sensor support
  6. Improved enclosure designs
  7. Localization for different regions
  8. Test your changes thoroughly
  9. Submit a pull request with detailed description

# Areas for Contribution
1. 🔋 Power management algorithms
2. 📡 Wireless protocol optimizations
3. 🌡️ Sensor calibration procedures
4. 🏠 Enclosure designs for different environments
5. 📊 Data visualization interfaces
6. 🔧 Manufacturing improvements

# License
This Environmental Sensor Node PCB design is licensed under the MIT License. See the [MIT License ↗](https://opensource.org/license/mit/) file for more information.
