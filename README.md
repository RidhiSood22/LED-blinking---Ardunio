# Single LED Blink - Tinkercad

# Overview
This project demonstrates how to make a single LED blink using an Arduino on Tinkercad. The LED will turn on and off repeatedly, simulating a blinking effect. This is a basic project, perfect for beginners who are learning about Arduino and basic circuit design.

# Components Required
1. Arduino Uno: The microcontroller that will control the LED.
2. Breadboard: A tool to connect the components without soldering.
3. LED: The light-emitting diode that will blink.
4. Resistor: To limit the current and prevent the LED from burning out.
5. Jumper Wires: To connect the components.
   
# Circuit Diagram
LED: Connect the anode (longer leg) of the LED to digital pin 13 of the Arduino.
Resistor: Connect one end of the 220Ω resistor to the cathode (shorter leg) of the LED and the other end to the ground (GND) on the Arduino.
Ground Connection: Make sure the GND pin on the Arduino is connected to the ground rail on the breadboard.

# How It Works
Setup: The pinMode() function is used to set pin 13 as an output pin.
Loop: The digitalWrite() function turns the LED on and off, while the delay() function pauses the program for a specified amount of time (1000 milliseconds = 1 second) between each state change.

# Simulation on Tinkercad
1. Create a new circuit in Tinkercad.
2. Drag and drop the Arduino Uno, LED, resistor, and jumper wires onto the workspace.
3. Connect the components as described in the Circuit Diagram section.
4. Copy and paste the Arduino code into the code editor.
5. Start the simulation to see the LED blink.
