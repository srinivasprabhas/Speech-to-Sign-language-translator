 Speech to Sign Language Translator 🤟
This project is a mini speech-to-sign language translator built using Python. It takes voice input from the user, converts it into text using speech recognition, and then translates that text into Indian Sign Language (ISL) by displaying relevant sign GIFs for each word.

🎯 Features
🎤 Converts speech to text using speech_recognition

🔡 Tokenizes text and maps it to corresponding ISL signs

📽️ Displays ISL signs as GIF animations for each word

📦 Simple UI for input and playback

🛠️ Technologies Used
Python

SpeechRecognition (for speech-to-text)

Pygame / Tkinter (for GUI & GIF playback)

OS & time modules (for file handling and control)

📁 How It Works
The user speaks into the microphone.

The program uses the speech_recognition module to convert speech to text.

Each recognized word is matched with a corresponding ISL GIF (stored locally).

The program plays the sign language animation one word at a time in sequence.

🔄 Future Improvements
Add support for full sentence gestures

Integrate with real-time webcam-based sign rendering

Include more regional languages and broader vocabulary

Improve GUI and accessibility features
