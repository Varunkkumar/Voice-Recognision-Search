# Voice Recognition Search

A Python application that uses speech recognition to perform web searches.

## Features
- Voice-activated search using microphone input
- Automatic browser launching for search results
- Supports multiple search engines
- Simple and intuitive interface

## Installation
1. Clone the repository:
```bash
git clone https://github.com/Varunkkumar/Voice-Recognision-Search.git
cd Voice-Recognision-Search
```

2. Create and activate a virtual environment:
```bash
python -m venv .venv
.venv\Scripts\activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

## Usage
Run the application:
```bash
python main.py
```

Speak clearly when prompted. The application will:
1. Listen for your voice command
2. Process the speech input
3. Open your default browser with search results

## Dependencies
- Python 3.7+
- SpeechRecognition
- PyAudio
- Selenium
- ChromeDriver

## Future Improvements
- Add support for more search engines
- Implement voice command history
- Add configuration options
- Improve error handling for microphone issues
