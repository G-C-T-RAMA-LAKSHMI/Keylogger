# Keylogger Project

This is a basic keylogger implemented in Python. It logs keystrokes and saves them to a file named `keylogger.txt`. The contents of the file are then sent to a specified email address.

## Features
- Captures all keystrokes.
- Logs keystrokes into a file.
- Sends the log file to an email address.
- Stops logging when the `Esc` key is pressed.

## Requirements
- Python 3.x
- Libraries: `pynput`, `smtplib`, `ssl`

## Usage
1. Install the required libraries:
   ```bash
   pip install pynput
