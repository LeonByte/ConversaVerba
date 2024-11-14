# ConversaVerba

**ConversaVerba** is an open-source, gamified language learning app designed to help users improve their speaking and listening skills through interactive conversations and voice recognition. The app focuses on providing an immersive experience, where users can practice speaking in their target language, track their progress, and get real-time feedback.

### **Why ConversaVerba?**

The app's unique approach is to encourage users to practice speaking their target language from day one. Unlike traditional language learning methods, ConversaVerba helps users become comfortable with **natural language acquisition** through voice-based interactions, mimicking how children learn their first language.

## Key Features:

- **Voice-based learning**: Users practice speaking and listening in their target language.
- **Real-time translation**: Convert phrases from a user's native language to the target language.
- **Gamified progress tracking**: Track user progress through levels, points, and challenges.
- **Interactive AI conversations**: Practice natural conversations with real-time feedback.
- **Open-source collaboration**: This project is open for contributors. If you're passionate about language learning or coding, we'd love for you to get involved!

## Technologies:

### **Translation:**

- **OpenNMT** – Open-source neural machine translation, offering a customizable and highly extensible translation service.
- **Apertium** – Open-source machine translation system for a variety of languages, especially useful for less commonly spoken languages.
- **DeepL API** – High-quality translation (Freemium) for the best translations, especially for European languages.

### **Speech Recognition:**

- **Mozilla DeepSpeech** – Open-source speech recognition system based on deep learning, ideal for offline usage.
- **Vosk** – Lightweight, offline-compatible speech recognition supporting multiple languages.

### **Text-to-Speech (TTS):**

- **Festival** – Open-source speech synthesis system, providing natural-sounding voices for TTS.
- **eSpeak NG** – Lightweight open-source TTS engine, offering a variety of language support and good offline capabilities.

### **Backend:**

- **Django + Django Rest Framework (DRF)** – A robust, scalable framework for handling the backend and providing REST APIs to the frontend.
- **FastAPI** – A high-performance alternative to Django for handling API requests, ideal for quick responses and async features.
- **Flask + SQLite** – Lightweight backend using Flask and SQLite for small-scale MVP versions.

## Getting Started

To set up this project locally:

### Prerequisites:

1. Install [Python 3.x](https://www.python.org/downloads/)
2. Install [Node.js](https://nodejs.org/) for the frontend (if using React)
3. Create an [OpenNMT](https://opennmt.net/) or [Apertium](https://www.apertium.org/) instance for translation APIs (optional).
4. Set up Mozilla DeepSpeech or Vosk for speech recognition and text-to-speech engines like Festival or eSpeak NG.

### Backend Setup:

1. Clone the repository:

   ```bash
   git clone https://github.com/LeonByte/ConversaVerba.git
   cd ConversaVerba/backend
   ```

2. Create and activate a virtual environment:

   ```bash
   python3 -m venv venv
   source venv/bin/activate  # For Linux/Mac
   venv\Scripts\activate     # For Windows
   ```

3. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

4. Start the Flask or Django app:
   ```bash
   python app.py   # For Flask
   python manage.py runserver   # For Django
   ```

### Frontend Setup:

1. Navigate to the frontend folder:

   ```bash
   cd ../frontend
   ```

2. Install the required dependencies:

   ```bash
   npm install
   ```

3. Run the frontend app:
   ```bash
   npm start
   ```

### API Configuration:

- Make sure to configure your environment variables for API keys (e.g., OpenNMT, Apertium, DeepL, Mozilla DeepSpeech, etc.).

## Contributing

ConversaVerba is an open-source project! If you're interested in contributing, follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes and commit them (`git commit -m 'Add new feature'`).
4. Push to your branch (`git push origin feature-branch`).
5. Create a pull request!

If you have suggestions or ideas, feel free to open an issue. We're looking forward to seeing how you can help improve this project!

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## Acknowledgements

- **OpenNMT**, **Apertium**, and **DeepL** for providing reliable and powerful translation tools.
- **Mozilla DeepSpeech** and **Vosk** for offering open-source speech recognition.
- **Festival** and **eSpeak NG** for providing open-source TTS solutions.
- **Django**, **FastAPI**, and **Flask** for making backend development faster and more efficient.
- **The open-source community** for helping make these technologies accessible.

---

## How to Use ConversaVerba

Once the app is set up and running, users will be able to:

1. Start a conversation by selecting their target language.
2. The app will prompt the user to speak, and it will recognize the speech via the Speech-to-Text engine.
3. Users will receive a response based on the recognized text, either through a translation or a simulated conversation with the AI.
4. The app will track progress through points and challenges, encouraging users to continue improving their language skills.

---

## Future Plans:

- Add more language options and support for custom language models.
- Implement more advanced conversational AI (e.g., sentiment analysis for better responses).
- Create a mobile app version (React Native or Flutter).
- Add user authentication and profile tracking.

---
