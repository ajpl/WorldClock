# WorldClock

This is a WorldClock implementation using Atmega 328 and DS1307 as a RTC.

## Inspiration

This project was inspired by [this](https://www.instructables.com/id/The-Wordclock-Grew-Up/) instructable that relies on a DS1302 instead of a DS1307. A couple of changes had to be made since these clocks work in different ways ([DS1302 Datasheet](https://datasheets.maximintegrated.com/en/ds/DS1302.pdf) and [DS1307 Datasheet](https://datasheets.maximintegrated.com/en/ds/DS1307.pdf)).

## How To
- Get all the parts necessary according to the Bill of Materials in Part 8 of the instructable linked above (for electronics you may use the schematic if you prefer)
- Etch the PCB using your favorite method or using a service like [OSH Park](https://oshpark.com)

- Flash the program into your Atmega 328 using your programmer of choice

- Solder every component into your PCB

- Test it out

- Follow the instructions linked above in order to build the clock's enclosure

- Put everything together

- Enjoy!


## Dependencies

- [RTC Lib](https://github.com/adafruit/RTClib)

