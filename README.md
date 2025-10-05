# Aesthetic Image Generator App
## About
Aesthetic ImageGen App is a simple yet powerful Streamlit-based web application that enhances your uploaded images using Google’s Gemini 2.5 Flash Image (Nano Banana) model.
It allows you to input creative prompts like “Make this image aesthetically pleasing…” and instantly generate an improved, visually appealing version of your image.

Built with:
🐍 Python
🎨 Streamlit
🧠 Gemini 2.5 Flash Image (Nano Banana)

---

## Features
* Clean, responsive Streamlit interface
* Upload images (.jpg, .jpeg, .png)
* Add custom text prompts
* Generate aesthetic images using Gemini AI
* Sidebar for API key entry and session management
* Inline display of both original and generated images

---

## Installation and Setup
1. Clone the repository
```
git clone https://github.com/yourusername/aesthetic-imagegen-app.git
cd aesthetic-imagegen-app
```
2. Create and activate a virtual environment (optional)
```
python -m venv venv
venv\Scripts\activate   # On Windows
source venv/bin/activate  # On Mac/Linux
```
3. Install dependencies
```
pip install -r requirements.txt
```

---

## Getting a Google Gemini API Key
Visit Google AI Studio
Sign in with your Google account
Generate a new API key
Copy and paste it into the sidebar of the app when prompted

---

## Running the App
```
streamlit run app.py
```

---

## How It Works
Upload an image
Enter or modify the text prompt (default: “Make this image aesthetically pleasing...”)
Click Generate Image
The app sends your input to Gemini 2.5 Flash Image (Nano Banana)
The generated aesthetic image is displayed next to the original


