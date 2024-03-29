# SmartAlarmClock
A smart alarm clock powered by ESPHome on an ESP8266. It will be contained within a 3D printed PLA enclosure.

Hardware:
-  ESP8266
-  MAX7219digit LED Matrix Display
-  2x Rotary Encoders
-  1x Pressure Alarm Switch Mat
-  1x Push Button for starting bedtime routine
-  1x piezo buzzer for sounding alarm

Functionality:

The alarm clock **shall**
- [x] Receive the current time from Home Assistant
- [x] Display the time received from Home Assistant on the MAX7219 LED Matrix
- [ ] Allow the user to control input_numbers in Home Assistant
- [x] provide a push button to allow the user to start the Bedtime Home Assistant Routine
- [ ] provide a piezo buzzer for sounding alarm
- [ ] not allow the alarm to stop sounding until the user is out of bed
- [x] have the brightness of the display able to be controlled through Home Assistant
- [x] turn off the display when sleep state is activated
