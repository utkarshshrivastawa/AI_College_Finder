 # 🎯 Project Overview
This project is an AI-powered College Recommendation System built using Gradio for the frontend and Google's Gemini (Generative AI) model for generating personalized college suggestions. The goal is to help Indian students find suitable colleges based on their academic background, entrance exam scores, subject stream (PCM/PCB/Commerce/Arts), interests, and career goals.

# ⚙️ Technology Stack
The application is built using Python, with Gradio used to create a user-friendly web interface and Google Generative AI (Gemini API) to generate context-aware responses. The system processes student inputs and prompts Gemini to return tailored college suggestions across three categories: top-tier institutions, private universities, and government/state colleges.

# 🧠 How It Works
Users enter basic information like their name, 10th and 12th scores, entrance exam performance (optional), preferred stream, interests, and state preference. A detailed prompt is crafted and sent to the Gemini model, which acts like an experienced Indian education counselor. The model returns a categorized list of colleges relevant to the student’s profile, offering practical and personalized guidance.

# 🔐 API Key & Configuration
To use the Gemini API, an API key from Google Generative AI is required. This project is configured to load the key securely from an environment variable named GEMINI_API_KEY. For safety, users should store this key in a .env file and avoid hardcoding it into the script.

# 🚀 Launch Instructions
Install the required libraries (gradio, google-generativeai), add your Gemini API key, and run the script using Python. A web interface will be launched where users can input their details and receive real-time college recommendations.
# 🚀🚀 Output 
![WhatsApp Image 2025-06-08 at 18 15 16_49e3ae8f](https://github.com/user-attachments/assets/f7a430d2-8aab-42de-b4ce-8cca0505c2d9)

