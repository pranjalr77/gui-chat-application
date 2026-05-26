# GUI-Based Chat Application

## Overview
A desktop client-server chat application enabling real-time text communication 
between two users over a local network using Java socket programming.

## Architecture
- **Server:** Listens on port 6001, accepts client connections, handles 
  message exchange
- **Client:** Connects to server via socket, sends and receives messages 
  in real time
- **Communication:** Java Socket Programming with DataInputStream 
  and DataOutputStream

## Features
- Real-time bidirectional text messaging
- WhatsApp-inspired GUI with message bubbles and timestamps
- Active status display
- Clean undecorated window design

## Tech Stack
- Java
- Java AWT & Swing (GUI)
- Socket Programming (java.net)
- DataInputStream / DataOutputStream

## How to Run
1. Compile both files:
   javac Client.java Server.java
2. Run Server first:
   java Server
3. Run Client in a separate terminal:
   java Client
4. Both windows open — type in either to chat in real time

## Project Structure
gui-chat-application/
│
├── Client.java     # Client-side GUI and socket connection
├── Server.java     # Server-side GUI and socket listener
└── icons/          # UI icons and profile images


