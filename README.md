# arduino-bot

arduino
johnny-five
bot

If you are using all of the motors, it does take up most of the digital IOs, but ONLY if you're using those motors:
All 6 analog input pins are available. They can also be used as digital pins (pins #14 thru 19)
Digital pin 2, and 13 are not used.
The following pins are in use only if the DC/Stepper noted is in use:
Digital pin 11: DC Motor #1 / Stepper #1 (activation/speed control)
Digital pin 3: DC Motor #2 / Stepper #1 (activation/speed control)
Digital pin 5: DC Motor #3 / Stepper #2 (activation/speed control)
Digital pin 6: DC Motor #4 / Stepper #2 (activation/speed control)

The following pins are in use if any DC/steppers are used
Digital pin 4, 7, 8 and 12 are used to drive the DC/Stepper motors via the 74HC595 serial-to-parallel latch

The following pins are used only if that particular servo is in use:
Digitals pin 9: Servo #1 control
Digital pin 10: Servo #2 control