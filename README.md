# 01-led-blinking
"My first embedded systems project-LED blinking"


Project 1: LED Blinking

Description
This is my first Embedded Systems project in which I made an LED blink using [Arduino Uno].

Hardware Used

* Board: [Arduino Uno]
* LED (Yellow)
* Resistor (220ohm)
* Breadboard
* Jumper wires

How It Works

The LED is connected to a digital pin. The code makes the pin HIGH and LOW with a delay, which makes the LED turn ON and OFF repeatedly.

Code:
​```cpp

void setup() {
  pinMode(12, OUTPUT);
}

void loop() {
  digitalWrite(12, HIGH);
  delay(100);

  digitalWrite(12, LOW);
  delay(100);
}
​```

Demo Video
(https://youtu.be/9Y90IqyfOjw?si=PsWyGZ37I-SWlu11)

What I Learned

* How digital output pins work
* How to use the delay() function
* Basic circuit wiring (LED + resistor)
