# Water Flow Meter
<h2>Description</h2>
This code is designed for a water flow meter that measures the flow of water and displays it on an LCD screen. It is written in C++ and is intended to be used on an Arduino board.
<h2>Requirements</h2>
To use this code, you will need the following hardware components:<br><br>

- An Arduino board<br>
- A water flow meter<br>
- An LCD screen<br>
- Jumper wires<br>
<h2>Installation</h2>
To use this code, follow these steps:<br><br>

1. Install the Arduino software on your computer.<br>
2. Connect the water flow meter to your Arduino board using jumper wires.<br>
3. Connect the LCD screen to your Arduino board using jumper wires.<br>
4. Open the Arduino software and copy and paste the code into a new sketch.<br>
5. Upload the sketch to your Arduino board.<br>
<h2>Usage</h2>
Once the code is uploaded to your Arduino board, the water flow meter will start measuring the flow of water. The LCD screen will display the current flow rate in mL/sec and the setpoint value. The setpoint value can be adjusted using the two push buttons connected to the board.

When the flow rate is below the setpoint, pin 4 of the board is set to LOW, and when it's above the setpoint, pin 4 is set to HIGH. You can also view the water flow rate on the serial monitor.
<h2>Note</h2>
Make sure that the water flow meter is compatible with the Arduino board before using this code. The pin numbers used in the code may need to be changed depending on the specific board being used. Additionally, the LCD address in the code should be changed to match the address of your specific LCD screen.
<h2>License</h2>
This code is licensed under the MIT License. See the LICENSE file for details.
