🗣️ Text-to-Speech Converter

A fun and interactive Text-to-Speech Web App built using HTML, CSS, and JavaScript 🎧
This project converts the text you type into natural-sounding speech using the Web Speech API available in modern browsers.

🚀 Project Overview

This is a simple web application that allows users to:

✍️ Type or paste any text in the text box

🎤 Select from multiple available voices

🔊 Click a button to hear the text spoken aloud

It’s a great beginner-friendly project for learning JavaScript DOM manipulation and Web APIs.

🧰 Technologies Used

HTML5 → Page structure

CSS3 → Styling and layout

JavaScript (ES6) → App logic and functionality

Web Speech API → Browser-based speech synthesis

⚙️ How It Works

The app uses the SpeechSynthesisUtterance() interface to create a speech object.

It fetches available voices from the system using speechSynthesis.getVoices().

When you type text and click Speak, the app reads it aloud using your chosen voice.
