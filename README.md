# Water Flow Detector

This Python script, designed for a Raspberry Pi, interfaces with a flow meter sensor to measure water flow rates and report the data. The `FlowMeter` class handles input pulses from the sensor, calculates the current flow rate in liters per minute (L/min), and includes a callback for pulse events. The `main` function configures GPIO pins, initializes the `FlowMeter` instance, and continuously collects and prints flow rate measurements along with timestamps. The script is intended for real-time water flow monitoring and serves as a foundational component for integrating with the SORACOM API for further IoT applications.

## Usage

1. Connect the flow meter sensor to GPIO pin 7 on the Raspberry Pi.
2. Execute the script to collect and display water flow rate measurements.

**Note:** Ensure accurate GPIO pin configuration and proper sensor connections for reliable data collection.
