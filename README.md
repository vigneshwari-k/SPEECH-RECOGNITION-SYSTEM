# SPEECH-RECOGNITION-SYSTEM

**COMPANY**: CODTECH IT SOLUTIONS

**NAME**: VIGNESHWARI K

**INTERN ID**:CT04DH911

**DOMAIN**: EMBEDDED SYSTEMS

**DURATION**: 4 WEEKS

**MENTOR**: NEELA SANTHOSH

Description:
This project is a simple serial-controlled LED system using Arduino Uno. It allows the user to turn an LED on or off by sending commands through the serial monitor of the Arduino IDE. The LED is connected to digital pin 12 on the Arduino via a current-limiting resistor, and the Arduino receives input commands via USB.
The user can send the command "1" to turn the LED ON or "0" to turn it OFF. Any other input will return an "Unknown command" message. The Arduino reads the input string using Serial.readStringUntil('\n'), ensuring that the command is fully captured until a newline character is received. It then trims any whitespace and checks the value to determine the appropriate action.
This setup introduces basic serial communication, digital output control, and conditional logic, making it ideal for beginners learning how to interact with Arduino through software input. It can also be extended for more complex automation tasks using serial input, Bluetooth modules, or even voice control systems.


code description:
ledPin is defined as pin 12 for the LED.
setup() sets the pin mode and begins serial communication at 9600 baud.
In loop(), the program waits for serial input.
If input is "1", the LED is turned ON.
If input is "0", the LED is turned OFF.
Any other input prints "Unknown command".
The use of readStringUntil('\n') makes the input handling cleaner and more reliable than reading one character at a time, especially for string-based control systems.

Applications:
Learning and Prototyping:
Perfect for beginners to learn about digital output, serial communication, and basic string processing with Arduino.
Remote Device Control:
This system can be expanded with Bluetooth (HC-05), Wi-Fi (ESP8266), or voice modules to create wireless or voice-activated lighting systems.
Automation Systems:
A base for smart lighting or small appliance control where commands can be issued through apps or cloud platforms.
Accessibility Projects:
Integrate with assistive technologies to help people with limited mobility control household electronics.
Speech-to-Hardware Systems:
Can serve as a core component in voice-controlled systems where speech recognition modules send "1" or "0" to trigger actions.
Testing and Debugging:
Useful in test environments where developers need to manually toggle outputs during hardware debugging sessions.

#output

<img width="488" height="283" alt="Image" src="https://github.com/user-attachments/assets/1840491f-3e86-4d68-93a6-2cae0fff8737" />



