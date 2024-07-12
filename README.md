# Linguify
Linguify aims to break down language barriers and empower universal access to information by converting text and videos into multiple languages. This project facilitates communication for those facing language barriers or literacy challenges.

## Features

- **Multilingual Text Conversion:** Converts text into multiple languages using state-of-the-art models like M2M100.
- **Document Translation:** Translates entire documents to various languages.
- **Speech-to-Text Conversion:** Converts spoken language in videos to text.
- **Language Detection:** Detects the language of the provided text or speech using xlm-roberta.
- **Voice Translation:** Translates the detected language and converts it back to speech using OpenAI Whisper and Google TTS.

## Technology Stack

- **Backend:** Flask, Python
- **Frontend:** Angular
- **Language Models:** M2M100, xlm-roberta
- **APIs:** OpenAI Whisper, Google TTS
- **Additional Libraries:** LangChain, Hugging Face Transformers

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Linguify.git
   cd Linguify
   ```

2. Install backend dependencies:
   ```bash
   cd Linguify-backend
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   pip install -r requirements.txt
   ```

3. Install frontend dependencies:
   ```bash
   cd ../Linguify-frontend
   npm install
   ```

## Running the Application

1. Start the backend server:
   ```bash
   cd Linguify-backend
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   flask run
   ```

2. Start the frontend server:
   ```bash
   cd ../Linguify-frontend
   ng serve
   ```

3. Open your browser and navigate to `http://localhost:4200`.

## Usage

1. **Text Conversion:**
   - Navigate to the Text Conversion section.
   - Enter the text and select the target language.
   - Click "Convert" to get the translated text.

2. **Document Translation:**
   - Navigate to the Document Translation section.
   - Upload the document and select the target language.
   - Click "Translate" to download the translated document.

3. **Speech-to-Text Conversion:**
   - Navigate to the Speech-to-Text section.
   - Upload the video file.
   - Click "Convert" to get the transcribed text.

4. **Language Detection:**
   - Navigate to the Language Detection section.
   - Enter the text or upload the audio file.
   - Click "Detect" to identify the language.

5. **Voice Translation:**
   - Navigate to the Voice Translation section.
   - Upload the video file and select the target language.
   - Click "Translate" to download the video with the translated audio.
