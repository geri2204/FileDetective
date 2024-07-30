# File Detective

## Overview

File Detective is a Python application with a graphical user interface (GUI) built using `tkinter` and `watchdog`. This application allows you to list files in a specified directory and monitor specific subdirectories named 'Beerkezett' for any file changes in real-time.

## Features

- **List All Files**: Displays all files in the specified directory and its subdirectories.
- **Monitor 'Beerkezett' Directories**: Continuously monitors directories named 'Beerkezett' for any file changes, including additions and deletions.
- **Real-Time Updates**: Updates the GUI to reflect changes in the 'Beerkezett' directories, with a visual indicator showing activity.

## Requirements

- Python 3.x
- `tkinter` (usually included with Python)
- `watchdog` (install via `pip install watchdog`)

## Usage

1. **Run the Application**: Execute the script to launch the GUI.
2. **Specify Directory**: Enter the path of the directory you want to inspect in the text field labeled "Vizsgálandó mappa útvonala:".
3. **List Files**: Click the "LISTÁZÁS" button to list all files and those in any 'Beerkezett' directories.
4. **Monitor Activity**: The application will display real-time updates for 'Beerkezett' directories, with an indicator turning green to show activity.

## Code Description

- **`BeerkezettEventHandler` Class**: Handles file system events and triggers a GUI refresh.
- **`list_files_in_directory` Function**: Lists all files in the directory and identifies those in 'Beerkezett' directories.
- **`display_files` Function**: Updates the GUI with the current list of files and starts monitoring.
- **`start_watching_beerkezett` Function**: Sets up file system monitoring for 'Beerkezett' directories.
- **`refresh_beerkezett_files` Function**: Refreshes the file list in the 'Beerkezett' directories in real-time.

## Contribution

Feel free to contribute to this project by opening issues or submitting pull requests. Improvements and bug fixes are always welcome.
