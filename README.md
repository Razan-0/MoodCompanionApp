# 🎯 AI Mood Companion

**Final Project – Shaqra University AI Bootcamp**  
**By:** Abdessamad Bourkibate  
**Organized by:** Shaqra University & Google Developer Student Club (GDSC)

---

## 🧠 Overview
**AI Mood Companion** is an interactive Python-based application developed as part of the **AI Bootcamp at Shaqra University**, in collaboration with the **Google Developer Student Club (GDSC)**.  

The project uses **Artificial Intelligence (AI)** and **Natural Language Processing (NLP)** to analyze and track users’ emotional states through their written reflections.  
It encourages self-awareness, provides motivational responses, and visualizes emotional trends over time.

---

## 🚀 Objectives
- Apply **NLP and AI concepts** learned during the bootcamp.  
- Build a tool that helps users reflect on their emotions.  
- Visualize emotional data for insight and personal growth.  
- Demonstrate practical implementation of AI using **Python**.

---

## ✨ Features
- 🧩 Real-time **sentiment analysis** (positive / neutral / negative).  
- 🗂️ Automatic **logging** of user input into a CSV file.  
- 📊 Visual **charts and trend analysis** for emotional tracking.  
- 🤖 Friendly **chatbot** offering motivational advice.  
- 💻 Easy to run on **Google Colab** or locally.  
- 🧮 Built-in commands for quick stats and data review.

---

## ⚙️ How to Run

### 1️⃣ Install Required Libraries

!pip install -r requirements.txt

2️⃣ Run the Main Script

!python main.py


3️⃣ Start Interacting

Type your feelings — the AI Companion will analyze your mood and provide feedback instantly.


🧭 Example Interaction

> I feel happy today because I achieved my goals.
Sentiment: Positive 😊
Response: That’s amazing! Keep that spirit up — consistency creates success! 🌟

> I’m feeling tired and a bit overwhelmed.
Sentiment: Negative 😔
Response: Take a deep breath. Rest is part of progress — you’ve got this! 💪

📊 Data Format (CSV)

Example of mood_log.csv file:

timestamp, text, sentiment_label, sentiment_score
2025-10-31T18:00:00Z,"I feel happy today",positive,0.87

🏗️ Project Structure


AI-Mood-Companion/
│
├── main.py
├── requirements.txt
├── mood_log.csv
├── config.yaml
├── utils/
│   ├── sentiment_analyzer.py
│   ├── mood_logger.py
│   └── visualization.py
└── README.md





Educational Context

This project was developed within the AI Bootcamp organized by:

🏫 Shaqra University
💡 Google Developer Student Club (GDSC)

It applies several core topics covered in the bootcamp:

Natural Language Processing (NLP)

AI model integration

Data visualization and trend analysis

Interactive Python scripting

🧩 Possible Extensions

🌐 Add a web interface using Flask or Streamlit.

🔐 Implement encrypted local storage for user privacy.

🌍 Add multilingual support (Arabic, English, French).

🧭 Predict mood trends based on previous entries.

📅 Integrate reminders or daily check-in notifications.





👨‍💻 Author

Abdessamad Bourkibate
AI & Cybersecurity Researcher
📍 Morocco

<img width="100" height="100" alt="e28a1ed7-d7f9-4ed3-825c-156b491d62f8" src="https://github.com/user-attachments/assets/cf51416e-8605-4e89-86e9-32d7882fb176" />



“Your emotions are meaningful data — let AI help you understand them.” 💫





<img width="534" height="510" alt="ai" src="https://github.com/user-attachments/assets/e930f8fe-a2db-49d2-b1de-323d8c46d93a" />




🪪 License

This project is released under the MIT License.
