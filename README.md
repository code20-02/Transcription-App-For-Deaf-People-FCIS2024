# Transcription App for Deaf People

## Overview
The Transcription App for Deaf People is designed to facilitate communication by converting speech to text, text to speech, and recognizing text from images. Leveraging advanced AI and ML technologies, it bridges the communication gap between the deaf and hearing communities.

## Features
- **Real-Time Speech-to-Text:** Converts spoken language into text with high accuracy.
- **Text-to-Speech:** Generates natural-sounding speech from text inputs.
- **Optical Character Recognition (OCR):** Extracts text from images, supporting various document types and handwritten notes.
- **Multilingual Support:** Provides translation services for international communication.
- **Secure Data Storage:** Ensures user data protection and compliance with data protection regulations.

## Technologies Used
- **Whisper Model:** For speech-to-text conversion.
- **SpeechT5 Model:** For text-to-speech conversion.
- **PaddleOCR:** For optical character recognition.

## Installation

### Prerequisites
- Node.js
- NPM or Yarn
- Python 3.7 or higher
- pip (Python package installer)
- Expo CLI (if using Expo)

### Setting Up the Environment

1. **Clone the Repository:**
    ```bash
    git clone https://github.com/code20-02/Transcription-App-For-Deaf-People-FCIS2024.git
    cd Transcription-App-For-Deaf-People-FCIS2024
    ```

2. **Create a Virtual Environment for Flask:**
    ```bash
    python -m venv venv
    source venv/bin/activate   # On Windows: venv\Scripts\activate
    ```

3. **Install Flask Dependencies:**
    ```bash
    pip install -r backend/requirements.txt
    ```

4. **Install React Native Dependencies:**
    ```bash
    cd frontend
    npm install   # Or yarn install
    ```

## Running the Application

### Starting the Flask Server
Navigate to the backend directory and start the Flask server:
```bash
cd backend
flask run
```
This command will start the server at http://0.0.0.0:5000.

## Starting the React Native App with Expo

Navigate to the frontend directory and start the React Native app using Expo:

```bash
cd frontend
npx expo start
