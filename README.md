# My_Alexa
# Alexa-like Voice Assistant

This Python project implements a voice-controlled assistant similar to Amazon Alexa using various libraries.

## Features

- **Voice Recognition:** Uses SpeechRecognition library to understand voice commands.
- **Text-to-Speech:** Utilizes pyttsx3 library to provide responses audibly.
- **Functionality:**
  - Plays songs from YouTube using pywhatkit.
  - Retrieves current time.
  - Provides brief information from Wikipedia.
  - Tells jokes using pyjokes.
  
## Setup

1. **Installation:**
   - Clone the repository: `git clone https://github.com/yourusername/alexa-like-voice-assistant.git`
   - Install dependencies: `pip install -r requirements.txt`

2. **Voice Configuration:**
   - Ensure microphone is connected and recognized by your system.

3. **API Keys:**
   - No API keys are required for the libraries used in this project.

## Usage

1. Run the script: `python alexa.py`
2. Wait for "Start Speaking!!" prompt.
3. Speak one of the supported commands:
   - "Play [song name]"
   - "What time is it?"
   - "Who is [person]?"
   - "Tell me a joke"
   - "Stop" (to exit)

## Notes

- Ensure a stable internet connection for Wikipedia and YouTube functionalities.
- Adjust ambient noise if recognition issues occur.

## Credits

- **SpeechRecognition:** Library for recognizing speech from audio sources.
- **pyttsx3:** Library for text-to-speech conversion.
- **pywhatkit:** Library to interact with YouTube.
- **wikipedia:** Library for fetching Wikipedia articles.
- **pyjokes:** Library for fetching jokes.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

---
