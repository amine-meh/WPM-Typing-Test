# WPM Typing Test

## Overview
This project is a simple **Words Per Minute (WPM) Typing Test** built using Python and the `curses` library. The application randomly selects a line of text from a file and challenges users to type it as quickly and accurately as possible. It calculates and displays the user's typing speed in words per minute.

## Features
- Displays a welcome screen before starting the test.
- Dynamically calculates WPM during the typing session.
- Provides real-time feedback with color-coded text:
  - **Green** for correct characters.
  - **Red** for incorrect characters.
- Ends the test when the user completes typing the target text.
- Allows users to retry or exit the application.

## Prerequisites
To run this project, you need:
- Python 3.x installed on your system.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/WPM-Typing-Test.git
   ```

2. Navigate to the project directory:
   ```bash
   cd WPM-Typing-Test
   ```

3. Ensure that `text.txt` exists in the same directory and contains multiple lines of text for the test.

## Usage
Run the program with the following command:
```bash
python wpm_typing_test.py
```

### Controls
- **Start**: Press any key to begin the test.
- **Typing**: Type the displayed text accurately.
- **Delete**: Use Backspace to correct mistakes.
- **Exit**: Press `Esc` to quit the test.

## File Structure
- `wpm_typing_test.py`: Main script for the typing test.
- `text.txt`: Text file containing lines of text used in the test.

## How It Works
1. **Welcome Screen**: The program displays a welcome message and waits for the user to start.
2. **Target Text**: A random line is selected from `text.txt` and displayed as the target text.
3. **Real-Time Feedback**: The user types the text, and the program checks each character:
   - Correct characters are highlighted in green.
   - Incorrect characters are highlighted in red.
4. **WPM Calculation**: The words per minute (WPM) score is updated and displayed based on the user's progress.
5. **Completion**: The test ends when the user correctly types the entire target text. The user can then retry or exit.

## Example
Here's how the application might look during a typing session:
```
The quick brown fox jumps over the lazy dog.
WPM: 42.3
```
- Correctly typed characters appear in green.
- Mistakes appear in red.

## Dependencies
This project relies on Python's built-in `curses` module. No external libraries are required.

## Contributing
Contributions are welcome! If you have ideas for improvement or new features, feel free to open an issue or submit a pull request.

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.

## Acknowledgments
- Thanks to the Python community for making development enjoyable.

---
Happy typing!
