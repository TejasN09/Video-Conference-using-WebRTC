# WebRTC Video Conference

This project is a simple implementation of a WebRTC-based video conferencing application.

## Features

- Real-time video conferencing using WebRTC technology.
- Dynamic room creation and joining.
- Simple and intuitive user interface.

# Technologies Used

- **WebRTC**: Enables real-time communication between web browsers.
- **Socket.IO**: Facilitates real-time bidirectional event-based communication between clients and servers.
- **HTML/CSS/JavaScript**: Frontend development technologies for building the user interface and client-side functionality.
- **STUN Server**: Facilitates NAT traversal by providing public IP addresses to clients.
- **TURN Server**: Acts as a relay for WebRTC connections when direct peer-to-peer communication is not possible due to network restrictions.

## Usage

To use this application, follow these steps:

1. Enter the desired room number in the input field.
2. Click the "CONNECT" button to join the video conference.
3. Enjoy real-time video conferencing with other participants.

# Note

This application is designed for two-person conferences only. More than two people cannot be in the same room simultaneously. Each conference requires a separate room, and participants need to join different rooms to initiate video conferencing sessions.
