# Image-to-Text-to-Audio
Mini Project 
# 🖼️📖🔊 Image to Text to Audio Converter

Welcome to the **Image-to-Text-to-Audio** project!  
This application takes an image as input, extracts any readable text using Optical Character Recognition (OCR), and then converts that text into human-like speech using Text-to-Speech (TTS) technology.

## 🚀 Features

- 📷 Upload an image (JPG, PNG, etc.)
- 🧠 Extracts embedded text from the image using **pytesseract**
- 🔉 Converts the extracted text into speech using **pyttsx3**
- 💾 Saves the audio file locally for playback

---

## 🛠️ Tech Stack

- **Python** 🐍
- **OpenCV** – for image processing
- **Pytesseract** – for OCR (text extraction)
- **pyttsx3** – for Text-to-Speech conversion

---

## 📂 Project Structure

```bash
Image-to-Text-to-Audio/
├── main.py              # Main script for image-to-audio conversion
├── test.jpg             # Sample image for testing
├── output.mp3           # Audio output (auto-generated)
└── README.md            # Project documentation (this file)
