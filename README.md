Podcastify is a web app that converts textbooks and academic documents into podcast-style audio. 
It features a Vue.js frontend for uploads, routing, and real-time feedback, and a Flask backend for file processing, audio generation, and API integration. 
It uses Voiceflow’s REST APIs for context-aware chatbot interactions.

Tech Stack: Flask, Python, CSS, JavaScript, Vue.js, Voiceflow API

Key Features:
- Upload textbooks/documents for analysis
- Context-aware chatbot powered by Voiceflow
- Generate podcast-style audio from content
- Real-time feedback with Vue.js + Axios
- Modular and scalable Flask backend

Setup / Run:

Backend:
cd backend
pip install -r requirements.txt
python app.py

Frontend:
cd frontend
npm install
npm run serve


Usage:
1. Upload a file
2. Interact with the chatbot
3. Listen to the generated podcast audio
