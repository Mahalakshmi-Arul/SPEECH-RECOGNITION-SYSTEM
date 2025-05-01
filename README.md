# SPEECH_RECOGNITION_SYSTEM

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: MAHALAKSHMI A

*INTERN ID*: CT04DA198

*DOMAIN*: EMBEDDED SYSTEMS

*DURATION*: 4 WEEKS

*MENTOR*: NEELA SANTOSH

*DESCRIPTION*:
Developed a Bluetooth-controlled home appliance system using an ESP32 microcontroller. The system allows users to control a light and a fan via Bluetooth by sending commands from a paired mobile device. Commands such as "turn on light", "turn off light", "turn on fan", "turn off fan", and "all off" are recognized and executed to control the state of connected devices. The system provides real-time feedback via the serial monitor, confirming the received command.

*KEY FEATURES*:
➤ Bluetooth communication established using the ESP32’s BluetoothSerial library.
➤ Supports commands to control light (pin 2) and fan (pin 4).
➤ Commands include "turn on light", "turn off light", "turn on fan", "turn off fan", and "all off".
➤ Commands are received and processed line by line, with trimming and string comparison for accuracy.
➤ Outputs are updated via digitalWrite() based on the received commands.
➤ Serial communication provides real-time feedback, showing the executed command.
➤ No debounce logic required as commands are processed only when a complete line (newline character) is received.

*PERIPHERALS USED*:
• ESP32 microcontroller (for Bluetooth communication)
• Light (connected to pin 2)
• Fan (connected to pin 4)
• Bluetooth-enabled mobile device for command input
