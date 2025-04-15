# J.A.R.V.I.S AI Assistant

J.A.R.V.I.S (Just A Rather Very Intelligent System) is a Python-based voice-controlled AI assistant that can perform various tasks through voice commands. It's designed to make your daily tasks easier and more efficient.

## Features

- **Voice Interaction**: Speak to J.A.R.V.I.S and get responses through voice
- **Time and Date**: Get current time and date information
- **Web Search**: Search on Google and YouTube
- **Wikipedia Integration**: Get information from Wikipedia
- **Email Management**: Send emails through voice commands
- **System Control**: 
  - Take screenshots
  - Monitor CPU and battery usage
  - Control system power (shutdown, restart, logout)
- **Entertainment**:
  - Play music and videos
  - Tell jokes
- **Smart Features**:
  - Remember important information
  - Personal greeting based on time of day
  - Contact management

## Requirements

- Python 3.x
- Required Python packages:
  ```
  pyttsx3
  speech_recognition
  wikipedia
  pyautogui
  psutil
  pyjokes
  wolframalpha
  pywhatkit
  ```

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/J.A.R.V.I.S-AI-Assistant.git
   cd J.A.R.V.I.S-AI-Assistant
   ```

2. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

3. Configure your email settings in `jarvis.py`:
   - Update the email and password in the `sendEmail` function
   - Configure your contacts in `contacts.py`

## Usage

1. Run the assistant:
   ```bash
   python jarvis.py
   ```

2. Start speaking commands after the welcome message. Some example commands:
   - "What time is it?"
   - "Search Google for artificial intelligence"
   - "Open YouTube"
   - "Tell me a joke"
   - "Send email"
   - "What's the date today?"

## Customization

- You can modify the `contacts.py` file to add your contacts
- Adjust voice settings in `jarvis.py` (voice type, speed, etc.)
- Add new features by extending the command processing logic

## Note

- Make sure you have a working microphone
- Internet connection is required for web searches and Wikipedia queries
- For email functionality, you need to enable "Less secure app access" in your Google account settings

## License

This project is open source and available under the MIT License.

## Author

Created by MAK