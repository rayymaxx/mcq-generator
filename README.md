📘 MCQ Generator – AI-Powered Question Creator
Welcome to the MCQ Generator, a Streamlit web app that uses advanced language models to generate multiple-choice questions (MCQs) from context-rich text or uploaded documents.

✨ Features
✅ Upload a text or PDF file and generate MCQs instantly

🤖 Powered by LangChain + OpenAI for natural language understanding

📄 View, edit, or copy the generated questions

💾 Export MCQs for learning, exams, or training

🌐 Deployable on Streamlit Cloud, Render, or locally

🚀 Getting Started
1. Clone the Repository
'''bash
git clone https://github.com/rayymaxx/mcq-generator.git
'''
cd mcq-generator
3. Install Dependencies
Make sure you're using Python 3.10–3.11 (avoid 3.13 due to some package compatibility issues):

bash
Copy
Edit
pip install -r requirements.txt
3. Add OpenAI API Key
Create a .env file:

env
Copy
Edit
OPENAI_API_KEY=your_openai_key_here
4. Run the App
streamlit run StreamlitAPP.py
🗂 Project Structure
mcq-generator/
│
├── experiment/                # Experiment notebooks and CSVs
│   └── machinelearning.csv
│
├── logs/                     # (Optional) Logging output
│
├── src/
│   └── mcqgenerator/         # Core logic modules
│       ├── MCQGenerator.py   # MCQ generation logic using LangChain/OpenAI
│       ├── utils.py          # Helper functions
│       └── logger.py         # Logging utilities
│
├── Response.json             # Sample or pre-generated responses
├── requirements.txt          # Python dependencies
├── StreamlitAPP.py           # Main Streamlit UI app
├── test.py                   # Tests or dev scripts
├── README.md                 # Project documentation (this file)
└── .env                      # (Ignored) API keys and secrets
📦 Requirements
Python 3.10+

Streamlit

OpenAI

LangChain

Pandas

Other dependencies listed in requirements.txt

🌍 Deployment
Deploy on Streamlit Cloud
Push to a GitHub repo

Go to streamlit.io/cloud

Connect your repo and set:

Main file: StreamlitAPP.py

Python version: >=3.10,<3.12

Secrets: Add OPENAI_API_KEY in the secrets manager

🧪 Example Usage
Launch the app

Upload a .txt file or input context manually

Click Generate MCQs

Review and export your results

🤝 Contributing
Pull requests are welcome! If you have suggestions for improvements or new features, feel free to fork the repo and create a PR.

⚠️ Disclaimer
This project is educational and experimental. Always verify AI-generated content for accuracy before using it in high-stakes environments like exams.

📧 Contact
Created by Raymond Odhiambo
GitHub: rayymaxx

