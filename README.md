# Chatbot with Gemini API — Text and Voice Interaction

## Overview

This project implements an intelligent chatbot powered by the Google Gemini API. The chatbot supports both textual and voice-based interactions, allowing users to communicate via typed messages or speech. It responds in natural language text as well as synthesized speech, providing a versatile conversational experience.

## Features

- Accepts user input as text or voice  
- Processes queries using Google Gemini generative AI API  
- Provides responses both in text and synthesized voice  
- Continuous interaction loop supporting multi-turn conversations  
- Easy to extend and integrate with other applications  

## Technologies Used

- Python 3.x  
- Google Gemini API (Generative Language SDK)  
- SpeechRecognition library for voice input  
- pyttsx3 (or gTTS) for text-to-speech output  
- Optional Streamlit web UI for enhanced user experience  

## Installation and Setup
1. **Clone the repository** 
   bash
   git clone https://github.com/naveennallathambi22/naveen.git
   cd naveen

2. **Install dependencies**
   bash
   pip install -r requirements.txt

3. **Obtain Google Gemini API key**

   * Visit [Google MakerSuite](https://makersuite.google.com/app/apikey)
   * Create and copy your API key

4. **Configure API key**

   * Set environment variable `GEMINI_API_KEY`
     bash
     export GEMINI_API_KEY="your_api_key_here"  # Linux/macOS
     set GEMINI_API_KEY="your_api_key_here"     # Windows CMD
     $env:GEMINI_API_KEY="your_api_key_here"    # PowerShell
     
   * Alternatively, store in a `.env` file and load via `python-dotenv`

## Usage

Run the chatbot script to start interaction:
bash
python chatbot.py


The chatbot will accept text or voice input, then respond both visually and via speech synthesis.

For an optional web interface, run:
bash
streamlit run app.py

## Project Structure


├── chatbot.py          # Main chatbot script with text & voice support
├── app.py              # Optional Streamlit web app interface
├── requirements.txt    # Python dependencies
├── README.md           # Project documentation
└── .env                # Environment variables (e.g., API keys)


## Future Work

* Integration with wake-word detection for hands-free activation
* Support for multiple languages and accents
* Improved conversation context retention
* Deployment as a web or mobile app

## Author

**Naveen N**
AI and Data Science Student | Data Analyst & AI Engineer
GitHub: [https://github.com/naveennallathambi22](https://github.com/naveennallathambi22)

