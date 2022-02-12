# Door-Counter

Welcome to the Door-Counter repo! The goal of this project is to give an accurate count of the number of people
that enter either of the two main enterances at Northview Church in Fargo, ND.

This repo was started by myself, Dylan Carlson, after joining the greeting team. The idea came to me during 
the kickoff meeting for the greeting team when people were discussing what the main enterance of the church was. 
(Northview is a pretty large church and there are two "main" enterances, but which is used more?)

Instead of trying to count people manually, an automated solution would make things a LOT easier. Also,
we can see how many people enter at specific times. There may be other benefits to knowing this information,
but it is mainly for fun.

The current hardware this is being tested on is a Raspberry Pi 3 B+, but this can in future be implemented
using a Raspberry Pi Zero since it is a much more cost effective solution.

## Ideas

The following are different ideas to try to find the best solution for counting people entering the church:
- Ultrasonic Sensor
    - This seems like the best solution so far, but it sometimes isn't the most reliable with objects that
    are not solid (ie pants, jackets, etc.) It is great for detecting distance.
- Laser Pointer
    - Placement is tricky for this, we don't want legs to count as two people, and we don't want a kid to look
    directly into the laser.
- Something counting the number of times door opened
    - May be inaccurate since door can be opened for multiple groups of people.

## References
- https://www.canakit.com/raspberry-pi-3-model-b-plus-ultimate-kit.html
    - Where Raspberry Pi was ordered from.
- https://tutorials-raspberrypi.com/raspberry-pi-ultrasonic-sensor-hc-sr04/
    - Ultrasonic sensor code and wiring diagram.
