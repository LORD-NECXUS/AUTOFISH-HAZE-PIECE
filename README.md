# Automatic Fishing Script for Roblox Haze Piece

This script allows you to fish automatically while you are AFK on the Roblox Haze Piece server. It is designed to automatically catch fish by detecting a red exclamation mark on the screen.

## Main Features

- **Automatic Mouse Coordinate Capture**: The script captures the mouse coordinates on the red exclamation mark above the character to automate clicks.
- **Automated Fishing Loop**: Once the coordinates are captured, the script runs a fishing loop, checks for the presence of fish, and triggers a series of clicks to catch them.
- **User Interface (GUI)**: The application features a simple user interface with buttons to capture coordinates, start and stop fishing, and display the number of fish caught.
- **Multi-Language Support**: The interface supports multiple languages (French, English, Russian, Spanish) to accommodate different users.
- **Message Display**: Actions and statuses of the script are shown in a text area, allowing the user to track what is happening in real-time.
- **Credits and YouTube Link**: A link to the creator's YouTube channel is integrated into the interface.

### How the Script Works

- **Coordinate Capture**: The user must click on a red exclamation mark located above the character to capture its coordinates. Once captured, fishing can begin.
- **Fishing Loop**: After fishing starts, the script simulates clicks to begin fishing. It periodically checks for the presence of a fish by analyzing the color of the pixel at the captured coordinates.
- **Fish Detection**: If a fish is detected (based on the red hue of the pixel), the script triggers a series of clicks to catch the fish.
- **Error Handling**: If an error occurs during fish detection, an error message is displayed to the user.

## Installation

To install the script, go to the **Releases** section of the project and download the latest available version.

---

**Note**: This script is intended for use in a specific environment (Roblox Haze Piece) and requires the user to configure settings correctly to function effectively.
