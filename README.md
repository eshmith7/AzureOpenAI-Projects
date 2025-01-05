# Azure OpenAI Projects

## Overview
This repository contains AI-driven applications using Azure OpenAI services, including GPT (chat completion), Whisper (speech-to-text), DALL-E 3 (image generation), and a Flask-based chatbot. These projects demonstrate real-world use cases such as handling user queries, generating images, transcribing audio, and retrieving real-time weather data.

## Projects Included

### 1. **Chat Completion (`chat_completion.py`)**
Generates chat responses using Azure OpenAI's GPT model.

**Key Features**:
- Initializes an Azure OpenAI client.
- Sends a user query and retrieves a response.

**Usage**:
```bash
python chat_completion.py
```

---

### 2. **Function Calling (`funcation_calling.py`)**
Retrieves real-time weather data using function calling and the OpenWeatherMap API.

**Key Features**:
- Defines a function schema for weather retrieval.
- Sends a query and invokes the function to fetch weather data.

**Usage**:
```bash
python funcation_calling.py
```

---

### 3. **Whisper Speech-to-Text (`whisper.py`)**
Transcribes audio files into text using Azure OpenAI’s Whisper model and generates a chat response based on the transcription.

**Key Features**:
- Sends an audio file to the Whisper model for transcription.
- Uses the transcribed text as input for a chat completion.

**Usage**:
```bash
python whisper.py
```

---

### 4. **DALL-E 3 Image Generation (`dalle3.py`)**
Generates images from text prompts using Azure OpenAI’s DALL-E 3 model.

**Key Features**:
- Sends a text prompt to the DALL-E 3 model.
- Retrieves and prints the URL of the generated image.

**Usage**:
```bash
python dalle3.py
```

---

### 5. **Flask Web App (`app.py`)**
A Flask-based chatbot that interacts with an Azure ML endpoint.

**Key Features**:
- Provides a web interface for user queries.
- Sends queries to an Azure ML endpoint and displays responses.

**Usage**:
```bash
python app.py
```
Access the web app at `http://localhost:5000`.
