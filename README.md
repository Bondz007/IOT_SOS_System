# SOS System 🆘

## Components
- Xiao C2 board
- A9G board
- PCB Board
- Batteries

## Project Overview
### Research and Component Selection
- Conducted comprehensive research to select suitable components.
- Chose Xiao C2 and A9G boards, integrated them with emergency buttons.

### Device Development
- Setup of A9G board for GPS-based location tracking.
- Implemented functionality for sending emergency alerts and making calls.

### Testing and Validation
- Thoroughly tested the device for accuracy in location sharing and emergency call functionalities.
- Real-world testing involved public distribution and feedback collection.

## Features
- Emergency Alerts: Triggered by pressing the SOS button for 5 seconds.
- Location Sharing: Automatically sends GPS coordinates to the guardian.
- Emergency Calls: Enables two-way communication between the user and guardian.

## Code Overview (Refer to file attched below)
The provided code snippet initializes the A9G board and manages communication for location sharing and emergency calls. Key functionalities include:
- Setting up communication protocols (AT commands).
- Managing GPS data retrieval and formatting for Google Maps links.
- Handling incoming requests (SEND LOCATION, RING, NO CARRIER) from the guardian device.

## Setup Instructions
### Hardware Setup
- Connect Xiao C2 and A9G boards as per the circuit diagram.
- Ensure proper power supply and button connections.

### Software Setup
- Upload the provided Arduino sketch to the Xiao C2 board.
- Adjust configurations like SOS number and SOS button timing (SOS_Time).

### Deployment
- Place the device where it can be easily accessed during emergencies.
- Ensure the device has a clear view of the sky for GPS reception.

## Troubleshooting
- If GPS data retrieval fails, ensure the A9G board has an active GPS fix.
- Verify SIM card connectivity and network signal strength.
