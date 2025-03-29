# Components Used:

Microcontroller: Arduino Uno

Soil Moisture Sensor

DHT11/DHT22 Temperature & Humidity Sensor

Relay Module

Water Pump

16x2 LCD Display (I2C Module)

ESP8266 WiFi Module (Optional for IoT)
# Working
The soil moisture sensor detects soil dryness.

If the moisture level is below a predefined threshold, the relay module activates the water pump to irrigate the soil.

The DHT sensor records temperature and humidity data.

The LCD display shows real-time sensor readings.

(Optional) The ESP8266 module sends data to a cloud platform for remote access.
Installation & Usage

Hardware Setup:

Connect the sensors, relay module, LCD, and water pump as per the circuit diagram.

Upload Code:

Open the provided Arduino code in the Arduino IDE.

Select the correct board (Arduino Uno) and COM port.

Upload the code to the board.

Running the System:

Power the Arduino and components.

The system will automatically read sensor values and control irrigation.

Monitor readings on the LCD display.

