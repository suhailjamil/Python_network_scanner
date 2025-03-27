Simple Network Scanner

A lightweight Python tool for discovering and identifying devices on your local network.

Features

Scans local network for active devices

Identifies known devices based on MAC addresses

Generates a report of known and unknown devices

Creates log files for each scan

Quick Start
1.Clone the repository

2.Install dependencies:
pip install -r requirements.txt

3.Run the scanner:
python main.py


Configuration
Add known devices to data/devices.json:

{
  "00:11:22:33:44:55": {
    "type": "Smartphone",
    "owner": "Alice",
    "location": "Living Room",
    "allowed": true
  }
}


Output
The scanner provides:

Console output with device tables

Daily log files in the data/ directory

