# Unified-Spech-Recognition-System# 🎙️ Real-Time Subtitling, Audio Search & Virtual Support System

This project is a multi-functional system that integrates **real-time subtitling for live events**, **audio content search and indexing**, and a **virtual customer support system** using speech and language processing technologies.

---

## 🚀 Features

### 1. Real-Time Subtitling for Live Events
- Uses automatic speech recognition (ASR) to transcribe live audio into subtitles.
- Supports live audio streams (e.g., microphone or broadcast feed).
- Outputs captions in real-time via web UI or CLI.

### 2. Audio Content Search and Index
- Indexes audio archives by transcribing content.
- Allows semantic search over large audio datasets.
- Employs vector similarity search using FAISS and transformer-based embeddings.

### 3. Virtual Customer Support System
- Provides voice and text-based support to users.
- Integrates a dialogue system (e.g., GPT or Rasa).
- Capable of understanding user queries and responding naturally.

---

## 🛠️ Technologies Used

- **Python 3.9+**
- **SpeechRecognition / Whisper / Vosk** (ASR engines)
- **Transformers (HuggingFace)** – for embeddings and language modeling
- **FAISS** – fast vector search
- **Flask / FastAPI** – backend API
- **WebSockets / Socket.IO** – real-time streaming
- **HTML/CSS/JS** – web UI for real-time captioning

---

## 📦 Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/realtime-subtitles-audio-search-support.git
cd realtime-subtitles-audio-search-support

# Create virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

