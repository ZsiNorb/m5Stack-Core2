# m5Stack-Core2
m5Stack Core2 v1.3 yaml for ESPHome Home Assistant

Bought an m5Stack Core2 v1.3 and wasn't able to find a working yaml file for it. There's a good documentation on the device but getting it to work with ESP was a pain. Thought it would be easier for all to have a working code in hand. 

Please note that I'm a complete amateur and my code is purely for my enjoyment. You can request extras, happy to look into them but I'm nowhere near to any programmers here on this forum.

As this is my first project on this site, please don't be toxic. Thank you kindly.

Why does this project exist?
Wanted a fun little gimmick device and see how stupid ideas I can actually get away with in Home Assistant. For instance, now I can automate if a button is pressed on a given page outside the ESP needs only on Home Assistant instead of playing with the ESP code all the time. It saves me quite a time and energy.

- Stupid project 1: check the accelerator as it measures gravity values. If X changes to 0.1, it's rotated left so I can lower the room brightness or curtains to an appropriate value.
- Stupid project 2: depending on which page is currently being showed, the buttons act differently
- Stupid project 3: show different pages depending on room usage, show different page if I'm at my table or when I'm at somewhere else allowing more control of smart home


Functions:
- Display works (was the hardest to get it to work)
- Wifi works
- Has HTTP enabled
- Can set brightness (note that if it's less than x amount, the backlight turns off, play with it)
- Battery level, voltage, current
- 2 pages configured yet, just for fun, can take more (added a page number report to HA so it can be monitored from there as well)
- Gyro, roll and accelerator
- Temp sensor
- 3 buttons


To be fixed:
- buzzer is missing
- touch coordinations to be added
