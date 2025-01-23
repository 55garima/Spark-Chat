# Spark Chat: Real-Time WebSocket Messaging Application

## Overview
Spark Chat is a lightweight, real-time web chat application built with Flask and SocketIO, enabling instant communication across multiple browser instances.

## Features
- Instant message broadcasting
- Username customization
- Timestamped messages
- WebSocket-powered real-time communication

## Prerequisites
- Python 3.8+
- pip

## Setup
1. Clone repository
2. Create virtual environment
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```
3. Install dependencies
   ```bash
   pip install -r requirements.txt
   ```

## Running Application
```bash
python chat.py
```
Access at `http://localhost:5000`

## Technologies
- Flask
- Flask-SocketIO
- JavaScript

## License
MIT License