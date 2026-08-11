Nurse Call System

Overview
	Node monitors critical events specifically “Code Blue” emergencies and general “Assistance” requests and transmit these events to a centralized HiveMQ Cloud Dashboard via MQTT.

Key Features
	Emergency Alerting: Dual-button system for differentiating between high-priority (code blue) and standard (assistance) calls.
	IoT Connectivity: Secure Wi-Fi connectivity with real-time MQTT telemetry.
	Built-in Feedback: Utilizes the ESP32-S3 onboard RGB LED for visual status indicator and external LEDS for ESP32-C3 and wt32 eth01.
		Red: Code Blue
		Yellow/Green: Assistance
		Off: System Reset

Firmware Requirements
ESP32 Board Package: Install the ESP32 board manager by Espressif.

Libraries:
PubSubClient (for MQTT communication)
    	Adafruit_NeoPixel (for controlling the onboard RGB LED)

Configuration
SSID and Password: Local Wi-Fi credentials.
MQTT Server: HiveMQ broker address.
MQTT User and MQTT password: MQTT authentication credentials.
ROOM_NUMBER: 
Room 1_node1 - Esp32-C3 
Room 2_node2 - WT32 ETH01
Room3_node3 – ESP32-S3

