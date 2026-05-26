#  Smart Hydration Reminder

##  Project Overview

The **Smart Hydration Reminder** is an Arduino-based system that monitors the surrounding temperature using a temperature sensor. When the temperature reaches **30°C or higher**, the system alerts the user to drink water through a buzzer, LED indicator, and LCD message.

This project helps promote proper hydration and prevents dehydration during hot weather conditions.

---

##  Objective

- Monitor ambient temperature in real-time
- Alert the user when temperature exceeds 30°C
- Encourage hydration during hot weather
- Display temperature readings using an LCD screen

---

##  Components Used

- Arduino Uno  
- TMP36 Temperature Sensor  
- 16x2 I2C LCD Display  
- LED  
- Buzzer  
- 220Ω Resistor  
- Jumper Wires  
- Breadboard  

---

##  How It Works

1. The TMP36 sensor reads the surrounding temperature.
2. Arduino converts the analog signal into Celsius value.
3. Temperature is displayed on the LCD screen.
4. If temperature is **≥ 30°C**:
   - LED turns ON  
   - Buzzer sounds  
   - LCD shows "Drink Water!"
5. If temperature is normal:
   - LED and buzzer are OFF  
   - LCD shows "Temp Normal"

---
