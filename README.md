# FAQ Chatbot (TF-IDF + Flask)

This project is an AI-powered FAQ chatbot that answers customer questions using **TF-IDF** and COSINE SIMILARITIES.  
It can run locally in Jupyter or integrate with Twilio WhatsApp via a Flask API.

## Features
- Trains a chatbot from your FAQ CSV (`newfaq.csv`)
- Responds to similar questions using cosine similarity
- Redirects unclear queries to a human provider
- Flask webhook endpoint ready for Twilio WhatsApp

## Technologies
- Python
- Flask
- Scikit-learn
- Twilio API
- Jupyter Notebook

#Setup Instructions
1. Clone the repo:
   ```bash
   git clone https://github.com/<your-username>/faq_chatbot.git
   cd faq_chatbot
