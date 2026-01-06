# Java Mail Client-Server Application

This repository contains a **Java-based email application** developed as part of the *Programming 3* course.

The system follows a **client-server architecture** and supports concurrent communication between multiple clients using **sockets and multithreading**, with a graphical user interface implemented in **JavaFX**.

---

## Architecture Overview

The application is composed of:

- **Mail Server**
  - Manages client connections
  - Handles message delivery and storage
  - Supports concurrent clients through multithreading

- **Mail Clients**
  - Connect to the server via sockets
  - Provide a graphical interface for email management
  - Communicate asynchronously with the server

Each client runs in its own process and interacts with the server using a custom communication protocol.

---

## Core Features

The application supports common email functionalities, including:

- User authentication (login)
- Sending emails to one or more recipients
- Carbon copy (**CC**)
- Forwarding messages
- Replying to received emails
- Inbox management through a graphical interface

---

## Concurrency and Networking

Key technical aspects of the project include:

- **Socket-based communication** for message exchange
- **Multithreading** to handle multiple simultaneous client connections
- Thread-safe handling of shared server resources
- Separation between networking logic and UI logic

---

## Graphical User Interface

The client application features a GUI built with **JavaFX**, providing:

- Login interface
- Mail composition and reading views
- User-friendly interaction with server-side functionality

The UI is designed to remain responsive while network operations are handled in background threads.

---

## Technologies Used

- **Java**
- **JavaFX**
- **Sockets**
- **Multithreading**
- Client-server architecture

---
