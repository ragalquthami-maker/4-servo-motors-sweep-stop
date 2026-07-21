# 4-servo-motors-sweep-stop

This code makes 4 servo motors move together. First they sweep back and forth for 2 seconds, then they stop and stay fixed at 90 degrees.

Wiring:
- Servo 1 → Pin 9
- Servo 2 → Pin 10
- Servo 3 → Pin 11
- Servo 4 → Pin 12
- All red wires → 5V
- All black/brown wires → GND

How it works:
The program uses a timer (`millis()`) to count 2 seconds. During that time, all servos move from 0° to 180° and back repeatedly.

This is a photo taken during the sweep movement, showing the servos moving:

![Sweep Movement 1](sweep-movement-1.jpeg)

This is another photo during the sweep movement:

![Sweep Movement 2](sweep-movement-2.jpeg)

Once the 2 seconds pass, all servos jump to 90° and stay there they don't move again.

This is a photo taken after the servos stopped and locked at 90 degrees:

![Stop at 90 Degrees](stop-90-degrees.jpeg)

This is the video showing the full process from start to finish, including both movements:
Video path: servo-simulation.mp4
[servo-simulation.mp4](servo-simulation.mp4)
