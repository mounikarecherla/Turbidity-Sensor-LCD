# Turbidity Sensor with LCD Display

This Arduino project uses a turbidity sensor to measure water clarity and displays the status on a 16x2 LCD using the LiquidCrystal_I2C library.

## 💡 Features

- Measures water turbidity using an analog sensor
- Displays "CLEAR", "CLOUDY", or "DIRTY" on the LCD
- Uses LED indicators to represent status levels

## 🛠️ Components Used

- Arduino Uno
- Turbidity Sensor
- 16x2 LCD (I2C)
- LEDs (Red, Yellow, Green)
- Resistors
- Breadboard and jumper wires

## 📟 Output Ranges

- `< 20` – CLEAR (Green LED)
- `10 – 50` – CLOUDY (Yellow LED)
- `> 50` – DIRTY (Red LED)

## 🧪 Library

- `LiquidCrystal_I2C.h`

> Ensure the correct I2C address (0x27) and pin configuration for your LCD.

