
# GUI-Based Chat Application

## Overview
A desktop client-server chat application enabling real-time text communication between two users over a local network using Java socket programming.

## Architecture
- **Server:** Listens on port 6001, accepts client connections, handles message exchange
- **Client:** Connects to server via socket, sends and receives messages in real time
- **Communication:** Java Socket Programming with DataInputStream and DataOutputStream

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
1. Create Java Project named: Chat App
2. Keep both the java files: Server.java, Client.java inside src as shown below
   src->chatting->application-> Client.java, Server.java
3. In src, keep icons folder containing all images
4. Compile both files:
   javac -d bin src/chatting/application/*.java
5. Run Server first:
   java -cp bin chatting.application.Server
6. Run Client in a separate terminal:
   java -cp bin chatting.application.Client
7. Both windows open — type in either to chat in real time

## Project Structure
- Chat App/src/chatting/application/ Client.java
- Chat App/src/chatting/application/ Server.java
- Chat App/src/icons/ #containing all images

## References
- www.youtube.com
- www.geeksforgeeks.org
