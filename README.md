# Single-Push-Relay-Latch-Motor-Control-Circuit
Single-Push Relay Latch Motor Control Circuit

This project is a relay-based latching motor control circuit powered by two separate supplies (12V control circuit and 8V motor supply). The system is designed so that:
A single press of the push button (SW1 or SW2 depending on wiring) activates the relay.
Once activated, the relay latches itself ON, meaning it stays energized even after releasing the push button.
The relay contacts then supply power to the motor (MT1), causing it to start rotating.
The motor continues running without needing to hold the push button.
The only way to stop the motor is by turning OFF the main 12V supply switch, which breaks the latch and de-energizes the relay.

How It Works

Pressing the push button momentarily energizes the relay coil (RL1).
One of the relay contacts feeds power back to its own coil (self-holding path).
This creates a latching effect (memory function).
The second relay contact connects the 8V battery to the motor.
When the 12V supply is switched OFF, the relay loses power and resets.

<img width="1090" height="646" alt="image" src="https://github.com/user-attachments/assets/91658352-b39e-4f91-8dbf-8009f9cc614f" />
<img width="698" height="394" alt="image" src="https://github.com/user-attachments/assets/9f2b0e5f-234c-4b16-9b81-b249c60c0315" />
