# Multitype Summarization App

This is a **Multitype Summarization App** built with Streamlit that extracts and summarizes text from various input sources, including text, images, PDFs, audio files, videos, and YouTube links. The app uses the BART model from Hugging Face Transformers for summarization, alongside several other libraries for processing different media types.

## Features

- **Text Summarization**: Summarizes plain text.
- **Image Summarization**: Extracts and summarizes text from images.
- **PDF Summarization**: Extracts and summarizes text from PDFs.
- **YouTube Video Summarization**: Extracts audio from a YouTube link, transcribes it, and provides a summary.
- **Video Summarization**: Summarizes text from video files by extracting audio and transcribing it.
- **Audio Summarization**: Summarizes content from audio files.

## Requirements

To run this app, ensure you have the following dependencies:

- `fitz` (PyMuPDF): for PDF handling
- `Pillow`: for image processing
- `pytesseract`: for OCR text extraction from images
- `transformers`: for text summarization using the BART model
- `streamlit`: for web app interface
- `speech_recognition`: for audio transcription
- `pytube`: for YouTube video handling
- `requests`: for HTTP requests
- `moviepy`: for handling video and audio conversion

You can install these dependencies using:
pip install PyMuPDF Pillow pytesseract transformers streamlit speechrecognition pytube requests moviepy


Usage
Open the app in a browser after starting Streamlit.
Upload a file or provide text input in the appropriate section.
Click on the "Summarize" button to see the summary for the input.
Notes
This app is in an initial phase and may not produce the best summaries in all cases.
For images, PDFs, and audio, ensure clarity and quality for optimal summarization results.
Contributing
Contributions are welcome! Feel free to fork this repository and submit a pull request.
