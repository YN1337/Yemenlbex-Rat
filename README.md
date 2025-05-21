# Yemenlbex-Rat

Yemen Ibex: Remote Administration Tool
Overview
Yemen Ibex is a powerful remote administration tool (RAT) designed for system administrators and security professionals. It provides a sleek, web-based interface for managing and monitoring remote systems with comprehensive visualization and control features.
Key Features
Real-time Client Monitoring: Track connected systems with status indicators
Interactive World Map: Visualize client locations with animated connections
Remote Command Execution: Execute shell commands on remote systems
File System Management: Browse, download, and upload files on remote systems
Screen Capture: Take screenshots of remote desktops
Webcam Access: Capture webcam images from remote systems
Browser Credential Collection: Securely extract and transfer browser data
Keylogging Capabilities: Monitor keyboard input on remote systems
System Notifications: Send alerts to connected clients
Setup Instructions
Prerequisites
Python 3.8 or higher
Required Python packages (install using pip install -r requirements.txt):
flask
flask-socketio
python-engineio
python-socketio
Jinja2
opencv-python
pynput
pyautogui
Pillow
requests
eventlet
pycryptodome
pywin32 (Windows only)
Installation
Clone or download the Yemen Ibex repository
Navigate to the project directory
Install dependencies:
Apply to payload.py
Running the Tool
Starting the Server
Run the server using one of these methods:
Method 1 - Using run.py (recommended):
Apply to payload.py
Method 2 - Direct server execution:
Apply to payload.py
The server will start on port 8443 by default. A browser window should automatically open to http://localhost:8443.
Command-line Options
Apply to payload.py
Available options:
--host: Server host (default: 0.0.0.0)
--port: Server port (default: 8443)
--no-browser: Don't open browser automatically
--debug: Run in debug mode
Basic Usage
Access the web interface at http://localhost:8443
The Dashboard shows server stats and connected clients
The Clients page displays all connected systems
Use the Control button to access remote system features
The Interactive Map shows global client distribution
The About section contains tool information and credits
Legal Disclaimer
Yemen Ibex is intended for EDUCATIONAL AND AUTHORIZED USE ONLY. Using this tool on systems without explicit permission is illegal and unethical. The developers assume no liability for misuse of this software.
Created by YE1337 - For educational purposes only.
