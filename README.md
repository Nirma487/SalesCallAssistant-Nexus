SalesCallAssistant-Nexus

SalesCallAssistant-Nexus is an AI-powered sales call assistant designed to help sales teams manage conversations, analyze customer sentiment, authenticate users securely, and store call session data efficiently.

The system integrates backend intelligence with optional frontend support to streamline sales engagement and improve conversion effectiveness.

📌 Overview

SalesCallAssistant-Nexus provides:

Intelligent call handling logic

Customer sentiment analysis

Secure token-based authentication

Session logging and storage

MongoDB database integration

Modular and scalable backend architecture

This project is suitable for academic projects, AI experimentation, and real-world sales automation prototypes.

🛠️ Technology Stack

Python 3.x

MongoDB

PyMongo

NLP libraries (for sentiment analysis)

Optional React frontend

Shell scripting for deployment

📂 Project Structure
SalesCallAssistant-Nexus/
│
├── agent.py                  # Core AI sales agent logic
├── auth.py                   # Authentication system
├── create_token.py           # Token generation utility
├── main.py                   # Main application entry point
├── main1.py                  # Alternate execution script
├── sentiment_analysis.py     # Sentiment analysis module
├── test_mongo.py             # MongoDB connectivity testing
├── view_analysis1.py         # Analysis viewer utilities
├── sessions.json             # Stored session data
├── start.sh                  # Startup script
├── requirements.txt          # Project dependencies
└── agent-starter-react/      # Optional frontend (if used)

⚙️ Installation & Setup
1️⃣ Clone the Repository
git clone https://github.com/Nirma487/SalesCallAssistant-Nexus.git
cd SalesCallAssistant-Nexus

2️⃣ Create Virtual Environment

Windows:

python -m venv venv
venv\Scripts\activate


macOS/Linux:

python3 -m venv venv
source venv/bin/activate

3️⃣ Install Dependencies
pip install -r requirements.txt

🔐 Environment Configuration

Create a .env file in the root directory and add:

MONGO_URI=your_mongodb_connection_string
SECRET_KEY=your_secret_key


Ensure MongoDB is running locally or connected via cloud (e.g., MongoDB Atlas).

🚀 Running the Application

Start the backend server:

python main.py


If using the React frontend:

cd agent-starter-react
npm install
npm start

🧠 How It Works

User authentication is handled via token-based security.

Sales conversations are processed by the AI agent.

Sentiment analysis is applied to customer responses.

Session data is stored in MongoDB.

Analytics can be viewed using analysis modules.
