##Simple Keylogger


This project implements a basic keylogger program in Python using the pynput library. The keylogger records and logs keystrokes, focusing on capturing the keys pressed and saving them to a file. Important: This project is for educational purposes only. Make sure you have permission before using it on any system.

Features
Logs all keystrokes, including letters, numbers, and special characters.
Handles special keys such as Space, Enter, and Backspace.
Stops logging when the Esc key is pressed.
Saves keystrokes to a specified file for later review.

Requirements
Python 3.x
pynput library (can be installed via pip)

Install `pynput` with:
```bash
pip install pynput
```

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/simple-keylogger.git
   cd simple-keylogger
   ```
2. Install dependencies:
   ```bash
   pip install pynput
   ```

## Usage
To run the keylogger, execute the following command:
```bash
python keylogger.py
```
This will start logging keystrokes in `key_log.txt`. Press the **Escape** key (`Esc`) to stop the keylogger.

Code Overview
Key Logging Function (on_press)
Listens for key presses and writes them to key_log.txt.
Logs standard keys directly.
Logs special keys with labels like [SPACE], [ENTER], and [BACKSPACE].
Key Release Function (on_release)
Stops the listener when the Esc key is pressed, ending the program.

### Code Explanation
- **on_press**: Logs each key press, including special keys.
- **on_release**: Stops logging when the `Esc` key is pressed.
- **Listener**: Monitors key press and release events.

## Features
- Logs each keystroke in real-time.
- Handles special keys like Space, Enter, and Backspace.
- Easy to start and stop by pressing `Esc`.

## Ethical and Legal Notice
This keylogger is intended for educational purposes only. Unauthorized use of keylogging software is illegal and may breach privacy laws. Only use this tool in controlled environments where you have explicit permission.

## Contributing
Contributions are welcome! Please fork the repository and make a pull request with any improvements or suggestions.

## License
This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.

