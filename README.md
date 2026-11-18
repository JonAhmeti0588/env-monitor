# env-monitor

env-monitor is a project that tracks the temperature, humidity and air pressure in a room and shows them on a live web dashboard.

It uses an ESP32 microcontroller and a BME280 sensor to measure the temperature, humidity and air pressure.

The data is sent over WiFi using MQTT to a backend, stored in a PostgreSQL database and shown on a live web dashboard.
