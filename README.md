# BatteryTester
Battery Tester is simple tool used to check how your battery is.
Equipements:

    -Arduino Uno.
    -3 LEDs (Green, Yellow, Red).
    -Zener Diode 5/7
    -4 Resistors (3/4 : 11-ohm, 1/4: 220-ohm).
    -Breadboard & Wires.

Code source of this project is included in: BatteryTester.ino file.
Insctructions:
I will now quickly go through the steps of putting this together below. Underneath the instructions you will find a circuit diagram if you find it easier just following that.

    1 -Wire the ground pin on the Arduino to the ground rail on the breadboard.
    2 -On the breadboard place the green, red and yellow LED’s. Connect the ground pins to the ground rail.
    3 -Place a 11-ohm resistor onto positive end of the LEDS then hook a wire from resistor to the relevant pins on the Arduino.
    4 -The following LEDS should connect to the relevant pin numbers.
        Red LED = 4
        Yellow LED = 3
        Green LED = 2
    5 -Now connect from analogue pin 0 (A0) to the breadboard. After this add a 220-ohm resistor and the Zener diode (with the line on Zener diode facing towards the Arduino). Finally have a loose wire coming from the other end to diode.
    6 -Finally have a lose wire connected to the ground rail.
