# Real-Time AI Voice Interaction Platform

This project connects an AI system to a user-facing interface that allows real-time, spoken interaction. Users can speak directly to the AI and receive both text-based and audio-based responses in real time.

---

## Features

- Speech-to-Text (STT): Converts spoken user input into text
- AI Response Generation: Generates intelligent replies using custom logic
- Text-to-Speech (TTS): Converts AI responses into speech
- Interactive Frontend: HTML/JavaScript interface for seamless communication

---

## Technologies Used

### Backend (Python)
- Flask: Lightweight web framework to serve API endpoints
- SpeechRecognition (or similar): Converts voice input to text
- Custom AI logic: Processes input and generates responses
- Text-to-Speech: Uses pyttsx3 or gTTS for audio output

### Frontend (HTML/CSS/JavaScript)
- HTML/CSS/JS: Builds the user interface
- JavaScript Fetch API: Handles communication with the backend

---

## How It Works

### User Input
- The user clicks a "Speak" button
- The browser records voice input and sends it to the Flask backend

### Backend Processing
- Flask receives and processes the audio input
- Speech is transcribed to text using STT
- The AI generates a response based on the input
- The response is converted to audio using a TTS engine

### Response Delivery
- The backend returns both the response text and the audio file
- The frontend displays the response and plays the audio

---

## Project Structure (Example)

