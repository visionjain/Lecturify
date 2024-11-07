# Lecturify: Lecture to Notes Converter

Lecturify is a simple and effective tool that converts lecture audio into structured notes and generates quizzes and flashcards based on the content. Using Gemini's LLM API for text processing and summarization, this project aims to streamline studying by providing organized, interactive resources.

## Features

- **Lecture to Notes**: Transcribes lecture audio and converts it into detailed, organized notes.
- **Quizzes & Flashcards**: Automatically generates quizzes and flashcards from lecture content to aid retention.
- **Streamlit Interface**: User-friendly UI for easy interaction and content review.

## Tech Stack

- **Streamlit** for UI
- **Gemini LLM API** for text processing
- **SpeechRecognition** for audio transcription
- **gTTS** (Google Text-to-Speech) for audio output

## Setup

1. **Clone the repo**:
    ```bash
    git clone https://github.com/visionjain/Lecturify
    cd Lecturify
    ```

2. **Install dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

3. **Run the app**:
    ```bash
    streamlit run final.py
    ```

## Usage

Upload or record lecture audio, review the generated notes, and interact with quizzes and flashcards for a comprehensive learning experience.
