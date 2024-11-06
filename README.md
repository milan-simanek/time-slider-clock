Time slider digital clock
=========================

Decisions
---------

* each digit has 3 sliders: left, middle, right
* sliders are powered by stepper motors
* each digit motors are controlled by a dedicated ATtiny microcontroller
* the clock has a main ATmega chip which controls all digits ATtiny chips, communicates to get time updates, reads buttons

