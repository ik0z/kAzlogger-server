# KeyServ

KeyServ is a C# application designed to monitor keystrokes and display them in real-time on a web interface. This application includes a web server that listens on port 7744, requires authentication, and serves an HTML page showing the captured keystrokes.

## Features

- **Live Keystroke Monitoring**: Capture and display keystrokes in real-time.
- **Web Interface**: A web server serves a dark-themed HTML page similar to Telegram's design.
- **Authentication**: Basic authentication is required to access the web interface.
- **Advanced Keylogger Functionality**: Captures a wide range of key events including special characters and function keys.


## Usage

1. Run the application. It will minimize to the system tray.
2. Access the web interface by navigating to `http://localhost:7744/index.html` in your web browser.
3. Authenticate using the credentials:
   - Username: `kaz`
   - Password: `Just_Test`

## Code Overview

### Key Components

- **Web Server**: Listens on port 7744 and handles HTTP requests for the index page and keystroke data.
- **Keylogger**: Captures keystrokes and stores them in memory.
- **HTML Interface**: Displays the captured keystrokes in a styled container.

### Authentication

Basic authentication is implemented. Modify the credentials in the `AuthenticateRequest` method as needed.

### Logging

Errors are logged to `error.log` in the application's directory.

## Disclaimer

**Warning:** This application is intended for educational purposes only. Unauthorized use of keylogging software is illegal and unethical. Ensure you have explicit permission from the owner of the device before running this application. The developer is not responsible for any misuse of this software.


## Acknowledgements

Powered by ENG. Khaled

---

