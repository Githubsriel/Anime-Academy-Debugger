# Anime Academy Debugger

## Overview
The **Anime Academy Debugger** is a Tampermonkey userscript designed to enhance your experience on the Anime Academy chat platform. It provides a suite of debugging tools, including real-time logging of chat events, a spam module, and a display of your current Socket ID. This script is particularly useful for developers or power users who want to monitor and interact with the chat system more effectively.

## Features
- **Real-time Event Logging**: Logs `DOM`, `EMIT`, and `RECV` events in a structured and easy-to-read format.
- **Spam Module**: Allows you to send repeated messages at a customizable interval.
- **Socket ID Display**: Shows your current Socket ID, which is useful for debugging connection issues.
- **Draggable Debugger Interface**: A resizable and movable debugger window for convenient access.

## Installation
1. Ensure you have the [Tampermonkey](https://www.tampermonkey.net/) extension installed in your browser.
2. Create a new script in Tampermonkey and paste the provided code into the editor.
3. Save the script and navigate to `https://anime.academy/chat`.
4. The debugger interface should appear on the page.

## Usage
### Debugger Interface
- **Drag the Title Bar**: Click and drag the title bar to move the debugger window around the screen.
- **Resize the Window**: Use the bottom-right corner to resize the debugger window.

### Event Logging
- The debugger logs three types of events:
  - **DOM**: Events related to the Document Object Model.
  - **EMIT**: Events emitted by your socket.
  - **RECV**: Events received by your socket.
- Each event is timestamped and displayed in a scrollable section.

### Spam Module
- **Input Field**: Enter the message you want to spam in the input field.
- **Start Spam**: Click the "Start Spam" button to begin sending the message repeatedly.
- **Stop Spam**: Click the "Stop Spam" button to stop the spam.

### Socket ID Display
- The current Socket ID is displayed in the top-right corner of the screen.
- If the socket is not connected, it will display "Socket ID: Not Connected".

## Customization
- **Spam Interval**: Adjust the interval at which spam messages are sent by modifying the `setInterval` value in the `startSpamBtn.onclick` function.
- **Styling**: Customize the appearance of the debugger by modifying the `Object.assign` styles in the script.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Author
- **Asriel**

## Contributing
Contributions are welcome! Please open an issue or submit a pull request if you have any improvements or bug fixes.

## Disclaimer
This script is intended for educational and debugging purposes only. Use it responsibly and respect the rules of the Anime Academy platform. The author is not responsible for any misuse of this script.

---

Enjoy debugging and enhancing your Anime Academy chat experience! 🚀
