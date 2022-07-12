# Access-control-System-with-GLCD Part 1

WOKWI SIMULATION LINK Part 1: https://wokwi.com/projects/308981483474780737
WOKWI SIMULATION LINK Part 2: https://wokwi.com/projects/313477479383695937

**Project Description **

Capacitive sensors provide an alternative to the traditional mechanical buttons 
and sliders in electronics. These sensors work by sensing a conductive object 
nearby rather than detecting the physical state of the device. One of the 
applications is for the access control system. It is important to make a clear 
distinction between authentication and access control. Correctly establishing 
the identity of the user is the responsibility of the authentication service. 
Access control assumes that authentication of the user has been successfully 
verified prior to the enforcement of access control. 

**Design Requirement Part 1 (simulation - Online) ** USING WOKWI
* Students will use the simulator to explore components includes 
keypad, SSD1306 OLED display and Arduino Mega microcontroller. 
* Program the microcontroller to read input from keypad and displaying 
the input in the display. Use the student ID of each member as the 
passcode. If the passcode is entered correctly, shows different 
symbol/figure for correct authentication, which can differentiate each 
member otherwise shows incorrect symbol/figure in the display 


**Design Requirement Part 2 (Simulation - Online) ** USING WOKWI
* Students will explore to use a button with the purpose for access 
control system  
* Students are required to design and implement access control system 
using, button, GLCD and microcontroller Mega 
* Graphical design to show graphical user interface. 
* The full operation and commands are as follows:  
o Your student ID of each member needs to be stored in the 
EEPROM of the embedded system as the correct 
password/authentication. 
o Use the first button pressing to indicate that the system in the 
user entering passcodes mode. 
o Use a duration of 10 seconds to press the correct number via 
the button 
o After 10 seconds, the selected digit will stay on display. 
o Repeat this until the whole digits of the password are entered. 
o Use 15 seconds or more to indicate all digits have been entered. 
o As soon all digits of the passcodes are entered, compare digits 
with the stored student IDs in the EEPROM. 
o If the entered password is similar to the digits in the EEPROM, 
display a correct symbol in the display to that how the 
authentication has been successfully verified to provide access 
control. 
o Otherwise, display symbol or text for incorrect passcodes.

**Important requirements:  **
i. The system is protected by a password, which is stored in the 
EEPROM. The default password is EEE20003. The password 
needs to be entered from serial monitor. When the system is 
started, it will wait for the string to be entered in the serial monitor 
and compared to the password stored in the EEPROM. If the 
password is corrected entered, it will continue further.  
ii. If the password is entered correctly, create menu in the serial 
monitor to select different options:  
* Option-1  change 3 members passcodes. write/read this data 
into the EEPROM. 
* Option-2  The data from the additional sensor. Write and read 
this data into the EEPROM (Note: if section iv is done)  
* Option-3 interrupt-driven programming. 
iii. If option-3 is selected, it will enter the main routine for the main 
task of the project. Here, the project needs to implement interrupt-
driven programming for the access control system. This can be 
done by using external and internal interrupts or their 
combination. There should be no significant delay in the interrupt 
service routine (ISR), which can degrade the system's overall 
performance. 
iv. For getting High Distinction in the Project Demonstration, you will 
need to add components from the simulator and write the 
routine/program to use the additional sensor for enhancing the 
product. The additional component should be able to relate back 
to the original task of the system. Interrupt-driven programming is 
needed. The components can be used, including photo-
resistor/sensor, DHT22 Digital Humidity and Temperature sensor, 
HC-SR04 Ultrasonic Distance Sensor and RTC (Real Time 
Clock). Other criteria for the HD will need to be satisfied, 
according to Rubrik. 
* Assignment due date: this is part of the assignment for Portfolio-Project 
Demonstration and Project Report. 
4. Project Components 
Part 1 and Part 2: Components from Simulator: keypad, SSD1306 OLED 
display and Arduino Mega microcontroller, button and additional chosen 
sensor. 
