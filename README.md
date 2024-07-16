
# Simple Text Editor

A basic text editor built with Python and Tkinter. This text editor allows you to create, open, edit, and save text files with ease. It also supports basic clipboard operations like cut, copy, and paste.

## Features

- Create new files
- Open existing text files
- Save files
- Cut, copy, and paste text
- Scrollable text area

## Requirements

- Python 3.x

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/kunall0880/simple-text-editor.git
    ```

2. Navigate to the project directory:
    ```sh
    cd simple-text-editor
    ```

## Usage

Run the text editor using Python:

```sh
python txt.py
```

### File Menu Options

- **New**: Clears the text area for a new file.
- **Open**: Opens a dialog to select and load a text file.
- **Save**: Opens a dialog to save the current text to a file.
- **Exit**: Closes the application.

### Edit Menu Options

- **Cut**: Cuts the selected text to the clipboard.
- **Copy**: Copies the selected text to the clipboard.
- **Paste**: Pastes text from the clipboard into the text area.

## Code Overview

### Main Functions

- `new_file()`: Clears the text area.
- `open_file()`: Opens a file dialog and loads the selected file into the text area.
- `save_file()`: Opens a file dialog to save the current text.
- `cut_text()`: Cuts the selected text to the clipboard.
- `copy_text()`: Copies the selected text to the clipboard.
- `paste_text()`: Pastes text from the clipboard into the text area.

### GUI Setup

- Creates the main window with a title.
- Sets up a frame and scrollbar for the text area.
- Configures the text widget to support word wrapping and undo.
- Sets up the main menu with File and Edit menus.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## Contact

For any questions or comments, please open an issue on GitHub or contact me at kunall0880@gmail.com.
