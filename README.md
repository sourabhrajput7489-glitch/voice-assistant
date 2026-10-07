# Voice Assistant

A simple Python-based voice assistant that listens to spoken commands and opens Google, YouTube, or Wikipedia searches in the default browser.

## Features
- Voice input using `SpeechRecognition`
- Text-to-speech output using `pyttsx3`
- Search Google, YouTube, or Wikipedia by voice
- Simple command loop with exit support
- Lightweight and beginner-friendly

## Requirements
- Python 3.8+
- A working microphone
- Internet connection for speech recognition and browser searches

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/sourabhrajput7489-glitch/voice-assistant.git
   cd voice-assistant
   ```

2. Create a virtual environment (optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate   # On Windows: venv\Scripts\activate
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

Run the assistant:

```bash
python voice_assistant.py
```

Example commands:
- "Google Python tutorial"
- "YouTube machine learning"
- "Wikipedia Albert Einstein"
- "Exit"

## Notes
- Speech recognition uses Google Speech Recognition via the internet.
- For best performance, speak clearly and avoid noisy environments.
- This project is designed as a simple assistant and can be extended with more features.

## License
This project is open source and available under the MIT License.
