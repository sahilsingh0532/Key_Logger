# Python Keylogger - Cybersecurity Project

## Project Overview

This project is a simple keylogger created using Python as part of a cybersecurity project. A keylogger is a tool that records all keyboard inputs on a system. This project is designed for educational purposes, helping you understand the importance of securing sensitive information and demonstrating potential risks associated with malicious keylogging software.

> **DISCLAIMER**: This keylogger is for educational and research purposes only. Do not use it for illegal activities. Unauthorized access to someone's computer or recording keystrokes without consent is illegal and unethical.

## Features
- Captures and logs all keyboard keystrokes.
- Saves logs to a file.
- Runs in the background.
- Lightweight and easy to implement using Python.

## Technologies Used
- **Python** (Programming Language)
- **pynput** (Python library for controlling and monitoring input devices)

## Prerequisites

Before running the keylogger, ensure you have the following:
- Python 3.x installed on your machine.
- Basic understanding of Python programming.
  
## Installation

1. Clone this repository or download the project files:
    ```bash
    git clone https://github.com/sahilsingh0532/Key_Logger.git
    cd key_logger
    ```

2. Install the required Python library: `pynput`. You can install it using `pip`:
    ```bash
    pip install pynput
    ```

## Running the Keylogger

To run the keylogger, follow these steps:

1. Open a terminal or command prompt and navigate to the project folder.

2. Run the Python script:
    ```bash
    python main.py
    ```

3. The keylogger will start recording keystrokes in the background. All captured keystrokes will be logged into a file (e.g., `log.txt`).

4. To stop the keylogger, you can terminate the script by closing the terminal or using a keyboard interrupt (`Ctrl + C`).
