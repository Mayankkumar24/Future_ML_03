                                               💬 Customer Support Chatbot
🧠 Overview
-------------
This project is an AI-powered Customer Support Chatbot built using Dialogflow and Flask, designed to provide instant and automated responses to customer queries.
The chatbot mimics real human interaction, offering 24×7 assistance for frequently asked questions — such as order status, product details, and general inquiries.

⚙️ Tech Stack
---------------
Frontend: HTML, CSS
Backend: Flask (Python)
NLP Engine: Dialogflow (Google Cloud)
Deployment: Render.com

🎯 Key Features
------------------
Conversational AI – Built using Google Dialogflow for natural and human-like responses.
Dynamic Flask Backend – Handles request–response cycles between Dialogflow and the web interface.
Web Integration – Seamlessly integrated into an HTML frontend with simple, responsive CSS.
Deployed on Render – Fully functional live chatbot accessible through the web.

🧩 Workflow
--------------
User Interaction: User enters a query in the chatbot window on the web interface.
Flask Backend: The query is sent to the Flask server.
Dialogflow Integration: Flask forwards the user’s query to the Dialogflow agent.
Response Generation: Dialogflow processes the intent and sends back a relevant response.
Frontend Display: The chatbot displays the response in a conversational format.

🚀 Deployment
--------------
The chatbot is deployed on Render.com for public access.
Render automatically detects the Flask environment and runs the app using the gunicorn web server.

🔗 Live Demo: Click Here to Chat! https://ecomchatbot.onrender.com/

💡 Future Enhancements
-----------------------
Add database connectivity to log and analyze user conversations.
Train the Dialogflow agent for multi-intent recognition and context-based follow-ups.
Integrate voice support using Google Speech API.
Add authentication for admin-based response control.
