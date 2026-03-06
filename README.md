# Emotion Detection Web Application

A Flask-based web application that analyzes text input and detects the underlying emotions using IBM Watson NLP. The app identifies five emotions — **anger**, **disgust**, **fear**, **joy**, and **sadness** — and determines the dominant emotion in the given text.

## Features

- Real-time emotion analysis of user-provided text
- Displays individual scores for each emotion
- Highlights the dominant emotion
- Clean web interface for easy interaction
- Error handling for invalid or blank input

## Tech Stack

- **Python 3**
- **Flask** — lightweight web framework
- **IBM Watson NLP** — emotion prediction API
- **HTML / JavaScript** — front-end interface

## Project Structure

```
oaqjp-final-project-emb-ai/
├── EmotionDetection/
│   ├── __init__.py
│   └── emotion_detection.py
├── templates/
│   └── index.html
├── static/
│   └── mywebscript.js
├── server.py
├── test_emotion_detection.py
└── README.md
```

## How to Run

1. Install dependencies:

   ```bash
   pip3 install flask requests
   ```

2. Start the server:

   ```bash
   python3 server.py
   ```

3. Open the application on port **5000**.

## Running Tests

Open a separate terminal and run:

```bash
python3 test_emotion_detection.py
```

This runs unit tests to verify that the emotion detector correctly identifies joy, anger, disgust, sadness, and fear from sample sentences.

---

> **Note:** Unfortunately, this project only works in the IBM Cloud IDE so far. The IBM Cloud IDE was provided in the course.
