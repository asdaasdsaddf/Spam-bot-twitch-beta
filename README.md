# Twitch Spam Bot

This program is a Twitch spam bot that allows you to automate the process of sending multiple messages in Twitch chat. It supports both terminal and GUI modes for user interaction.

## Features

- Sends multiple spam messages to a Twitch chat.
- Can be operated via the terminal or a graphical user interface (GUI).
- Automatically checks for updates.
- Displays messages in the terminal with colored ASCII art using `colorama`.

## Requirements

- Python 3.x
- PySimpleGUI
- requests
- keyboard
- webbrowser
- colorama

## Installation

1. Ensure you have Python 3.x installed on your system.
2. Install the required Python packages:
    ```sh
    pip install PySimpleGUI requests keyboard colorama
    ```

## Usage

1. Clone or download this repository to your local machine.
2. Run the script:
    ```sh
    python twitch_spam_bot.py
    ```
3. The script will clear the terminal and display an ASCII art banner.
4. The script will check for updates. If an update is required, you will be prompted to download it.
5. You will be asked whether you want to use the terminal or GUI mode:
    - **Terminal Mode**:
        1. Enter the number of times to spam the message.
        2. Enter the message to be spammed.
        3. Click on the message input area in Twitch chat and wait for 5 seconds.
        4. The bot will start sending messages automatically.
    - **GUI Mode**:
        1. Enter the number of times to spam the message in the input field.
        2. Enter the message to be spammed in the input field.
        3. Follow the instructions on the GUI to start the spamming process.

## Example

```sh
# Example usage in terminal mode
python twitch_spam_bot.py
