# DeepSeek Sensitive Hide

## Description
This userscript is designed to help you hide and replace sensitive data on the DeepSeek chat interface. It provides a user-friendly UI to manage sensitive words and their replacements, ensuring that sensitive information is not displayed in plain text.

## Features
- **Sensitive Data Replacement**: Automatically replaces sensitive words with user-defined replacements.
- **Case Sensitivity**: Option to toggle case sensitivity for word matching.
- **Dynamic Content Handling**: Observes DOM changes to ensure replacements are applied to dynamically loaded content.
- **Persistent Storage**: Saves sensitive data and settings in `localStorage` for persistence across sessions.
- **Theme Detection**: Automatically adjusts the UI to match the page's theme (light or dark).

## Installation
1. Install a userscript manager like [Tampermonkey](https://www.tampermonkey.net/) or [Greasemonkey](https://www.greasespot.net/).
2. Create a new userscript and paste the contents of the provided script into it.
3. Save the userscript and ensure it is enabled.

## Usage
1. Navigate to the DeepSeek chat interface.
2. Click the lock icon (🔒) in the top-right corner to open the Sensitive Data Hider popup.
3. Add sensitive words and their replacements using the input fields.
4. Toggle the case sensitivity checkbox as needed.
5. The script will automatically replace sensitive words in the chat interface.

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request with your changes.