# VoicePro AI - TTS & STT

VoicePro AI is a web application that allows users to convert text to speech (TTS) and speech to text (STT) directly from their browser. Using the Web Speech API, this app provides a seamless and interactive experience with voice recognition and synthesis features.

## Features

- **Text-to-Speech (TTS)**: 
  - Type text into the provided text area and click "Speak" to hear the text read aloud.
  - Uses the browser's `SpeechSynthesis` API.

- **Speech-to-Text (STT)**:
  - Click "Start Listening" to transcribe your speech into text.
  - Click "Stop Listening" to stop the transcription.
  - Uses the browser's `SpeechRecognition` API.

## Installation

### Prerequisites

- A modern web browser that supports the Web Speech API (e.g., Google Chrome).

### Steps

1. Clone or download the repository to your local machine.
2. Open the `index.html` file in your web browser.
3. Ensure you have an active internet connection, as speech synthesis and recognition rely on browser capabilities.

## Usage

1. Open the `index.html` file in your browser.
2. You will be presented with two options:
   - **Text-to-Speech (TTS)**: 
     - Enter any text in the provided input box and click "Speak" to hear it aloud.
   - **Speech-to-Text (STT)**:
     - Click "Start Listening" to start transcribing speech to text.
     - Click "Stop Listening" to stop the transcription.
     - The transcribed text will be displayed in the output section.
   
## Browser Support

- This application uses the **SpeechSynthesis** and **SpeechRecognition** Web APIs.
- Full support for these APIs is available in **Google Chrome**.
- If you encounter issues in other browsers (e.g., Firefox, Safari), please use Google Chrome for the best experience.

## Known Issues

- Speech recognition may not work as expected on some browsers other than Chrome.
- There may be limitations in speech recognition for noisy environments or strong accents.

## Contributing

Feel free to fork the repository and submit pull requests with any enhancements or fixes. Here are a few ways you can contribute:
- Improve accessibility or design.
- Add more languages and voices to TTS.
- Improve error handling and browser compatibility.

## License

This project is open-source and available under the [MIT License](LICENSE).

## Acknowledgments

- The speech synthesis and recognition features rely on the **Web Speech API** provided by modern browsers.
- Designed and developed with love by **VoicePro AI** team.

---

For any questions or suggestions, please feel free to contact us via email: **kodalishanmukh03@gmail.com**.
