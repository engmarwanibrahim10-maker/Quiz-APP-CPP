# 🧠 C++ Interactive Quiz System

A professional command-line application that allows users to take a technical quiz. The project is designed with a focus on modularity and clean code.

## 🚀 Features
- **Object-Oriented Design**: Each quiz question is treated as an independent object.
- **Immediate Feedback**: Users get instant notification if their answer is correct or wrong.
- **Score Tracking**: Automatic calculation of total score at the end of the session.
- **Case Sensitivity Handling**: Accepts both uppercase and lowercase inputs (A, B, C, D).

## 🛠️ Tech Stack
- **Language**: C++
- **Paradigm**: Object-Oriented Programming (OOP)
- **Compiler**: GCC / Clang / MSVC

## 📖 How it Works
The program defines a `Question` class that stores the question text, possible options, and the correct answer. The main loop iterates through an array of these objects, calling the `.ask()` method for each.

## 💻 How to Run
1. Clone the repository.
2. Compile the source code:
   ```bash
   g++ main.cpp -o quiz
