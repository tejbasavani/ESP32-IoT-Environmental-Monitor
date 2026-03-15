# Working Principle

The ESP32 IoT Environmental Monitoring System operates by continuously sensing environmental parameters and transmitting the data wirelessly.

The DHT sensor measures temperature and humidity from the surrounding environment. These sensor readings are periodically transmitted to the ESP32 microcontroller through digital communication.

The ESP32 processes the sensor data and formats it for transmission. Using its built-in WiFi capability, the microcontroller can send the collected data to an IoT platform, web server, or monitoring dashboard.

If an OLED display is connected, the system can also show real-time temperature and humidity readings locally.

The system continuously repeats this process, enabling real-time environmental monitoring.
