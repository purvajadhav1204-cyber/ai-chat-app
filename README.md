AI Chat Assistant (Gemini-Style)
A sleek, responsive AI Chat Application built with HTML5, CSS3, and JavaScript. This project integrates with the Hugging Face Inference API to provide real-time AI responses in a modern, user-friendly interface.

Features
Real-time AI Interaction: Connects to powerful Large Language Models (LLMs) via API for instant responses.

Responsive Design: Clean, modern UI optimized for both desktop and mobile viewing.

User-Centric UX: Includes a "Thinking..." loading state and automatic scroll-to-bottom functionality.

Robust Error Handling: Implemented fallback logic to manage API rate limits and connection issues gracefully.

Tech Stack
Frontend: HTML5, CSS3 (Flexbox/Grid)

Scripting: Vanilla JavaScript (ES6+)

API: Hugging Face Inference API 

Tools: VS Code, Live Server

Setup & Installation
Clone the Repository:

Bash
git clone https://github.com/yourusername/ai-chat-app.git
Add your API Key:
Open script.js and replace the HF_TOKEN variable with your personal Hugging Face token(hf_bJyzkbhNAzIUZZCLvuNnCHmuZBoQDqiku)

Run the Project:
Open the project folder in VS Code and use the Live Server extension to launch the app at http://127.0.0.1:5500.

Technical Challenges & Learnings
CORS Management: Navigated Cross-Origin Resource Sharing (CORS) restrictions by utilizing local development servers and exploring proxy-based solutions.

Asynchronous Programming: Mastered the use of async/await and the Fetch API to manage non-blocking network requests.

State Handling: Implemented logic to disable UI elements during API processing, preventing redundant requests and ensuring a smooth user experience.

