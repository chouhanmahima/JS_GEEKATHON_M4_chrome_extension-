# 🖌️Color Picker Chrome Extension

## Description
This Chrome extension provides a simple yet powerful color picker tool. It allows users to select colors from any part of the screen using an eyedropper tool, store multiple picked colors, view their hexadecimal and RGB values, copy color values to the clipboard, export picked colors as a text file, and clear the list of picked colors.

## Features
- **Color Picking**: Utilizes an eyedropper tool to pick colors from any part of the screen.
- **Storage**: Stores picked colors locally using the browser's localStorage API.
- **Color Information**: Displays hexadecimal and RGB values of picked colors.
- **Copy to Clipboard**: Allows users to copy color values to the clipboard with a single click.
- **Export**: Enables users to export the list of picked colors as a text file for future reference.
- **Clear All**: Provides an option to clear the list of picked colors.

## Installation
To install the Color Picker Chrome Extension:
1. Download or clone the repository to your local machine.
2. Open Google Chrome and navigate to `chrome://extensions/`.
3. Enable Developer mode by toggling the switch in the top right corner.
4. Click on the "Load unpacked" button and select the directory where the extension files are located.
5. The Color Picker extension should now be installed and visible in the Chrome toolbar.

## Usage
1. Click on the Color Picker extension icon in the Chrome toolbar.
2. Click on the "Pick Color" button to activate the eyedropper tool.
3. Click on any part of the screen to pick a color.
4. Picked colors will be displayed in the extension popup.
5. Click on a picked color to view its details, including hexadecimal and RGB values.
6. Use the "Copy" button to copy color values to the clipboard.
7. To export the list of picked colors, click on the "Export Color" button.
8. To clear all picked colors, click on the "Clear All" button.

## Screenshots

### Color Picker extension
![Screenshot (79)](https://github.com/chouhanmahima/JS_GEEKATHON_M4_chrome_extension-/assets/142296544/ebe31d40-26ff-4ecd-9993-73a0f89a4131)

### "Pick Color" button
![Screenshot (80)](https://github.com/chouhanmahima/JS_GEEKATHON_M4_chrome_extension-/assets/142296544/7b9cee29-7c07-4abd-a2c3-52924be65e88)

### Pick color from screen
![Screenshot (81)](https://github.com/chouhanmahima/JS_GEEKATHON_M4_chrome_extension-/assets/142296544/275899d1-c5c1-4e51-aacb-b6b41eb975cd)

### View picked color in the extension popup
![Screenshot (82)](https://github.com/chouhanmahima/JS_GEEKATHON_M4_chrome_extension-/assets/142296544/40c0fe8f-b510-406b-be19-cb1f6bfb6622)

### Export color list
![Screenshot (83)](https://github.com/chouhanmahima/JS_GEEKATHON_M4_chrome_extension-/assets/142296544/c06b366b-fe71-4892-9e3d-52e71ff06361)

### download colors
![Screenshot (84)](https://github.com/chouhanmahima/JS_GEEKATHON_M4_chrome_extension-/assets/142296544/272f1c4d-bc87-485e-adf9-800508623231)

### Display color details
![Screenshot (85)](https://github.com/chouhanmahima/JS_GEEKATHON_M4_chrome_extension-/assets/142296544/88886fa1-02a4-4c69-ab79-ac1817365ef5)



## New Things Learned
- Implementation of an eyedropper tool in a Chrome extension.
- Interacting with browser storage for local data persistence.
- Dynamically creating and managing popup UI elements.

## Difficulties Faced
- Understanding the structure and usage of the Chrome extension manifest.
- Implementing the eyedropper functionality while ensuring compatibility across different Chrome versions.
- Managing the UI interactions and state updates in response to user actions.

## Compatibility
The Color Picker Chrome Extension is compatible with Chrome browsers running on Windows, macOS, and Linux platforms.
