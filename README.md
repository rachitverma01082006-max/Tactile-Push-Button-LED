# Tactile Push Button Controlled LED

## About the Project
A simple electronics project demonstrating how a tactile push
button can be used to control an LED.

The Arduino is used only as a power source for the circuit.
No Arduino programming is required.

## Components Used

- Arduino UNO
- Breadboard
- Tactile push button
- Red LED
- Resistor
- Jumper wires

## Working Principle

The tactile push button acts as a momentary switch.

When the button is not pressed, the circuit path is open and
the LED remains OFF.

When the button is pressed, the switch completes the electrical
path, allowing current to flow through the LED. The LED turns ON.

When the button is released, the connection opens again and
the LED turns OFF.

## Tactile Switch Operation

A four-pin tactile switch contains two pairs of internally
connected pins.

When the button is released, the two sides of the switch are
electrically disconnected.

When the button is pressed, the two sides become connected,
allowing current to flow.

## What I Learned

- How a tactile push button works
- How to use a breadboard
- Basic LED interfacing
- LED polarity
- Current limiting using a resistor
- How a momentary switch controls a circuit
- Basic circuit troubleshooting

## Future Improvements

- Control the LED using an Arduino GPIO pin
- Read the push button using digitalRead()
- Implement button debouncing
- Add multiple LEDs and switches# Tactile-Push-Button-LED
A basic electronics project demonstrating LED control using a tactile push button, breadboard, and Arduino UNO as a power source.
