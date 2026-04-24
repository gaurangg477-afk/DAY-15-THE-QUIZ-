# Day 17 – Quiz Game (Object-Oriented Programming)

This project is part of **Day 17** of *Angela Yu’s 100 Days of Code: Python Bootcamp*.

The goal of this project is to build a **command-line Quiz Game** using **Object-Oriented Programming (OOP)** concepts such as classes, objects, attributes, and methods.

---

## 📌 Project Overview

The Quiz Game asks the user a series of **True/False questions**, checks their answers, and keeps track of the score.  
The project emphasizes **clean code structure** by splitting logic into multiple Python files.

---

## 🧠 Concepts Covered

- Classes and Objects  
- `__init__()` constructor  
- `self` keyword  
- Object attributes and methods  
- Separating code into multiple modules  
- Basic program flow control

---

## 📁 Project Structure

quiz-game/
│
├── main.py
├── question_model.py
├── quiz_brain.py
└── data.py


---

## 📄 File Description

### `question_model.py`
Defines the `Question` class, which represents a single quiz question.

### `data.py`
Contains quiz questions stored as a list of dictionaries.  
Each dictionary includes:
- Question text
- Correct answer (`True` / `False`)

### `quiz_brain.py`
Contains the `QuizBrain` class, which:
- Manages question flow
- Checks user answers
- Tracks the score

### `main.py`
The entry point of the program.  
It creates question objects, initializes the quiz, and runs the game loop.

---

## ▶️ How to Run the Project

1. Make sure Python is installed on your system (Python 3 recommended).
2. Clone the repository or download the files.
3. Open a terminal in the project folder.
4. Run:

```bash
python main.py
🧪 Sample Output
Q.1: A slug's blood is green. (True/False): True
You got it right!
Your score: 1/1

Q.2: The capital of Australia is Sydney. (True/False): False
You got it right!
Your score: 2/2

You've completed the quiz!
Final score: 2/2
🎯 Learning Outcome
By completing this project, you gain a solid foundation in Object-Oriented Programming, which is essential for building larger applications such as games, APIs, data analysis systems, and machine learning models.

🚀 Future Improvements
Add multiple-choice questions

Fetch questions from an API

Add difficulty levels

Implement a graphical user interface (GUI)

## Author 
Gaurang Sharma
