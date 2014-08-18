raspberrypi_to_led
==================

Blink an LED using the Raspberry Pi's GPIO Pins

All below are connected in series:
GPIO Pin 7 (3.3V) -> Positive end of LED
Negative LED -> 1kohm current limit resistor
1kohm -> GPIO Pin 6 (GND)
