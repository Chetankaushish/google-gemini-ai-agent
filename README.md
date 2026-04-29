# google-gemini-ai-agent
This project is a simple AI assistant created using Python and Google Gemini API. It can generate intelligent responses, work like a chatbot, and also supports voice interaction. The project was built in Jupyter Notebook and VS Code to explore Generative AI, API integration, and real-time AI communication in a beginner-friendly way.

# Features
AI chatbot using Google Gemini API
Real-time AI responses
Voice assistant support
Prompt-based interaction
Beginner-friendly Python project
Works in Jupyter Notebook and VS Code

# Technologies Used
Python
Google Gemini API
Jupyter Notebook
VS Code
SpeechRecognition
pyttsx3

# INSTALLATION
pip install google-generativeai
pip install speechrecognition pyttsx3 pyaudio

# Setup API Key
Generate your free Gemini API key from:
https://aistudio.google.com/app/apikey
Replace:
genai.configure(api_key="YOUR_API_KEY")
with your own API key.

# Example code 
import google.generativeai as genai

# Configure API Key
genai.configure(api_key="YOUR_API_KEY")

# Load Gemini Model
model = genai.GenerativeModel("models/gemini-2.5-flash")

# Generate Response
response = model.generate_content("What is Artificial Intelligence?")

print(response.text)

# Future Improvements
Web-based chatbot UI
Advanced voice commands
AI memory support
Streamlit web app
PDF and file analysis
AI coding assistant

# This project is created for learning and educational purposes.
