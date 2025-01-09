# Voice Assistant Project

## Vision
This project aims to create a voice-controlled virtual assistant named "Alex" that listens to voice commands, processes them, and performs tasks such as playing YouTube videos. The assistant is designed to provide a hands-free, user-friendly experience and can be further developed to include more advanced features.

---

## Flowchart

```plaintext
Start
 ↳ Initialize Speech Recognition and Text-to-Speech Engine
   ↳ Listen to the User's Voice Command
      ↳ Recognize and Process the Command
         ↳ If Command Includes 'Play':
             ↳ Extract Song Name
             ↳ Play Song on YouTube
         ↳ Else:
             ↳ Ask User to Repeat Command
End
```

---

## Contract Address
*Note: This project does not interact with blockchain technology and thus does not have a contract address.*

---

## Installation and Usage

### Prerequisites
- Python 3.x
- Required libraries:
  - `speech_recognition`
  - `pyttsx3`
  - `pywhatkit`

### Steps to Run
1. Install the required Python libraries using the following commands:
   ```bash
   pip install SpeechRecognition pyttsx3 pywhatkit
   ```
2. Save the code into a Python file, e.g., `voice_assistant.py`.
3. Run the script in your terminal:
   ```bash
   python voice_assistant.py
   ```
4. Speak your command after the prompt "listening..." appears.
5. Use "Alex" as a keyword to activate the assistant. For example:
   - "Alex play [song name]"

---

## Features
- **Speech Recognition**: Captures and interprets user voice input.
- **YouTube Integration**: Searches and plays videos directly on YouTube.
- **Text-to-Speech**: Provides audible feedback to the user.

---

## Future Scope
1. **Task Automation**: Add functionality for scheduling tasks, setting reminders, and sending emails.
2. **Multi-Language Support**: Enable recognition and response in multiple languages.
3. **Smart Home Integration**: Integrate with IoT devices for controlling smart home appliances.
4. **AI Integration**: Use NLP and machine learning for improved command understanding and personalization.
5. **Mobile Application**: Develop a mobile app for easier access.
6. **Blockchain Integration**: If needed, for secure and decentralized command logging.

---

## Disclaimer
This project is a basic implementation and is not production-ready. Please test thoroughly before deploying in any critical environment.

