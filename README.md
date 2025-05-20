# -Generative-AI-UPSC-PCS-Quiz-Generator
📄AI-powered quiz generator for UPSC and PCS exam preparation. Generate customizable, topic-specific practice questions with real-time scoring and analytics using Groq, LangChain, and Streamlit.

# 🧠 UPSC & PCS Quiz Generator

This is an AI-powered quiz generation tool tailored for UPSC and PCS aspirants. It dynamically creates topic-specific and difficulty-adjusted questions using **Groq LLM**, and presents them through an interactive **Streamlit** web interface.

Designed for educators, coaching centers, and self-learners, the system automates quiz creation, real-time scoring, and performance analytics — saving time and enhancing exam prep.

---

## 🔍 Features

- ✅ **Automatic Question Generation**  
  Create multiple choice and fill-in-the-blank questions with custom topics and difficulty levels using Groq LLM.

- 📊 **Real-Time Scoring & Feedback**  
  Track your quiz performance instantly and get question-wise explanations.

- 🧠 **Context-Aware Quizzes**  
  LangChain helps maintain quiz consistency and relevance with previous inputs.

- 📈 **Performance Tracking**  
  Analyze scores, track accuracy, and monitor topic-wise strengths.

- 💬 **Interactive UI**  
  Built with Streamlit for an easy, modern, and responsive user interface.

---

## 🛠️ Tech Stack

- **LLM**: Groq API
- **Framework**: LangChain
- **Frontend**: Streamlit
- **Data Handling**: Pandas
- **Language**: Python 3.10+

---

## 📁 Folder Structure
upsc-pcs-quiz-generator/
├── main.py # Streamlit UI
├── utils.py # Question generation logic
├── requirements.txt
├── .env # API keys (not uploaded)
├── results/ # Quiz result history
└── README.md

## Yaml file

---

## ⚙️ Setup Instructions

```bash
# Clone the repo
git clone https://github.com/yourusername/upsc-pcs-quiz-generator.git
cd upsc-pcs-quiz-generator

# Create a virtual environment
conda create -p env python=3.10 -y
conda activate env

# Install dependencies
pip install -r requirements.txt

# Add your API keys
touch .env
```
## 🔐 Environment Variables
```
GROQ_API_KEY=your_groq_api_key_here
```
## 🧪 Usage
Select exam type (UPSC / PCS)
Choose topic and difficulty
Start the quiz and answer questions
Submit to receive score and analysis
View history and export results

## 📈 Future Enhancements
True/False and Matching-type questions
User authentication and progress dashboard
Topic-wise leaderboard & peer comparison
Support for Hindi and other regional languages
Spaced repetition for revision

👤 Author
Arjun Singh Gangwar
M.Tech – Data Science, IIT Palakkad
📧 [arjungangwar3@gmail.com] | 🌐 LinkedIn 007arjungangwar
