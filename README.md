# 🗣️ Text-to-Speech Converter

![HTML5](https://img.shields.io/badge/HTML5-orange?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-blue?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-yellow?logo=javascript&logoColor=black)
![Open Source](https://img.shields.io/badge/Open%20Source-💻-brightgreen)
![Made with ❤️ by Aniket](https://img.shields.io/badge/Made%20with-❤️-red)

> 🎧 A fun browser-based app that turns your text into speech using JavaScript & Web Speech API.

---

## 🚀 **Overview**

This is a simple yet engaging **Text-to-Speech Web App** built using  
💡 **HTML**, **CSS**, and **JavaScript**.  

It allows users to:  
- ✍️ Type or paste text  
- 🔊 Convert text into speech  
- 🎤 Select from multiple voices (male/female, accents)  

Perfect for learning **DOM manipulation**, **Web APIs**, and **frontend logic**.

---

## 🧰 **Tech Stack**

| Tech | Description |
|------|-------------|
| 🧱 HTML5 | Structure and layout |
| 🎨 CSS3 | Styling and responsiveness |
| ⚙️ JavaScript (ES6) | Logic and interactivity |
| 🗣️ Web Speech API | Converts text to spoken output |

---

## ⚙️ **How It Works**

1. User types text in the **textarea**.  
2. App fetches available voices from the browser using `speechSynthesis.getVoices()`.  
3. On clicking **Speak**, it uses `SpeechSynthesisUtterance()` to read the text aloud.  

---

## 💻 **Setup & Usage**

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/text-to-speech.git
