# PWMGEN

## Handheld STM32 PWM Generator

* A 10mm x 10mm x 30mm PWM signal generator with duty, prescaler and frequency control. 
* Supports both 3.3v and 5v logic level outputs.
* Output PWM can source 500mA.
* Requires a 9VDC 600mA power supply (5.5mm x 2.1mm connector, Centre-Positive).

### TODO

* 5V PSU input (remove uA78M05C)
* Increase PWM source current capabilities. (Use bigger series pass transistor and regulators)
* Improve prescaler control input (use N-times throw switch and N-times GPIO input)

<img src="HW/PWMGEN/DOCS/PWMGEN.svg" width=1000 height=600>

