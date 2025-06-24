# yt_summarizer

This project allows users to summarize YouTube videos by extracting transcripts and generating summaries using NLP models. It's built with a Python Flask backend and is accessed through a Chrome extension.

## Features

- Extracts video transcripts using the YouTube Transcript API
- Generates text summaries using Hugging Face models
- Designed to work as a Chrome extension for ease of use

## Technologies

- Python
- Flask
- YouTube Transcript API
- Hugging Face Transformers

## Setup Instructions

1. Clone the repository:

2. Install dependencies:

3. Run the backend:

4. Load the Chrome extension:
- Open Google Chrome and go to `chrome://extensions`
- Enable **Developer mode** (top right)
- Click **Load unpacked**
- Select the `extension/` folder from the project directory

## Notes

- You may need a Hugging Face API key if you are using hosted models.
- The extension makes requests to the Flask backend to process and return summaries.
