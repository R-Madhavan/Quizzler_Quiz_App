# Quizzler - Quiz Application

Quizzler is a Python-based quiz application with a graphical interface. This app fetches trivia questions from the Open Trivia Database (OpenTDB) and allows users to answer True/False questions, tracking their score as they progress.

## Features

- **Interactive GUI**: Uses Tkinter for a user-friendly interface.
- **Real-time Questions**: Fetches quiz questions via API from OpenTDB.
- **Score Tracking**: Keeps track of user scores and displays them after each question.
- **Feedback Mechanism**: Visual feedback indicating correct or incorrect answers.
- **End of Quiz Notification**: Notifies users when they've completed the quiz.

## How It Works

1. **Fetching Questions**: 
   - The app fetches 10 True/False questions from the Open Trivia Database API in JSON format.
2. **Quiz Interface**:
   - The interface displays questions on a canvas and has True/False buttons for user input.
3. **Score Display**:
   - The current score is displayed and updated after each question.
4. **Answer Feedback**:
   - The canvas changes color to green or red, indicating if the answer was correct or incorrect.
5. **End of Quiz**:
   - Once all questions are answered, the buttons are disabled, and a final message is displayed.

## Project Structure

```
├── main.py                 # Main script to run the application
├── question_model.py       # Contains the Question class for handling question objects
├── quiz_brain.py           # Manages quiz flow and answer validation
├── ui.py                   # GUI code for displaying the quiz interface
├── data.py                 # Fetches data from the Open Trivia Database API
└── images/                 # Contains images for True/False buttons
```

## Requirements

- Python 3.x
- `requests` library (for fetching questions from the API)
- `tkinter` (usually comes pre-installed with Python)

## Output

![quizzlerappvideo](https://github.com/user-attachments/assets/8ebbe9e4-cf4e-4f26-b3dd-41711dfdbe40)

## Credits

- [Open Trivia Database (OpenTDB)](https://opentdb.com) for the quiz questions.
