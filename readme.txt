Language Translator with Speech Recognition and Text-to-Speech
This is a simple Python-based language translation app using Google Translate, Speech Recognition, and Text-to-Speech. The app allows users to translate text between languages, convert spoken words into text, and hear the translated text aloud.

Features:

Text Translation: Translate any text between two languages.
Speech Recognition: Convert spoken words to text using voice input.
Text-to-Speech: Speak out the translated text using text-to-speech functionality.
Translation History: View the history of previous translations.

Technologies Used:

Google Translate API: For translating text between different languages.
SpeechRecognition: For converting speech to text.
pyttsx3: For converting text to speech.
Tkinter: For creating the graphical user interface (GUI).

Requirements:

1.Python 3.x
2.Install the following libraries:
3.googletrans==4.0.0-rc1
4.SpeechRecognition
5.pyttsx3
6.tkinter (comes pre-installed with Python)

How to Use:

Enter Text: Type text into the text field and select source and target languages (e.g., 'en' for English, 'es' for Spanish).
Translate: Click the "Translate" button to get the translated text.
Voice Input: Use the "Voice Input" button to convert your speech to text and automatically insert it into the input field.
Text-to-Speech: Click the "Speak" button to hear the translated text.
Show History: View previous translations by clicking the "Show History" button.

Future Enhancements:

Adding more language support for translation and speech recognition.
Improving the user interface for a better user experience.
Adding support for offline text-to-speech voices.

License:

This project is open source and available under the MIT License.