# 🎯 Interactive Quizzler

A Python GUI quiz application that fetches real-time True/False trivia questions from the Open Trivia Database API and displays them using a Tkinter interface.

The application allows users to answer questions interactively while tracking their score.

---

## 🚀 Features

- Dynamic trivia questions fetched from the Open Trivia Database API
- Interactive graphical interface using Tkinter
- Real-time score tracking
- Automatic question loading
- Simple and clean UI

---

## 🛠 Technologies Used

- Python
- Tkinter
- Requests library
- Open Trivia Database API

API Source:
https://opentdb.com/

---

## 📂 Project Structure

interactive_quizzler
│
├── main.py
├── quiz_brain.py
├── question_model.py
├── data.py
├── ui.py
│
├── images
│   ├── true.png
│   └── false.png
│
└── README.md

---

## ⚙️ Installation

Clone the repository

git clone https://github.com/sudinkatuwal7/interactive_quizzler.git

Navigate to the project folder

cd interactive_quizzler

Install dependencies

pip install requests

Run the application

python main.py

---

## 🧠 How It Works

1. The program requests trivia questions from the Open Trivia Database API.
2. The API returns questions in JSON format.
3. The data is converted into Question objects.
4. The QuizBrain class manages the quiz logic and scoring.
5. The Tkinter interface displays the questions and buttons.

---

## 📌 Future Improvements

- Difficulty selection
- Multiple choice questions
- Timer for questions
- Leaderboard system
- Improved UI design

---

## 👨‍💻 Author

Sudin Katuwal  
GitHub: https://github.com/sudinkatuwal7