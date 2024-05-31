# React Quiz App 🎓

This is an interactive quiz application built with React. The app features a multiple-choice questions (MCQs) format, along with a starting screen, an ending screen, high scores, and a progress bar to track your progress through the quiz.

## Features ✨

- **Multiple Choice Questions**: Answer a series of MCQs to test your knowledge.
- **Starting Screen**: Begin the quiz from an engaging starting screen.
- **Ending Screen**: See your results and score at the end of the quiz.
- **High Scores**: Track and display the highest scores achieved.
- **Progress Bar**: Visually track your progress through the quiz.

## Technologies Used 🛠️

- **React**: The project is built with React, a JavaScript library for building user interfaces.
- **useReducer Hook**: Used to manage complex state logic in the app, such as quiz state and score updates.
- **Context API**: Provides a way to share state across the app without prop drilling, used for managing the global state like user scores and quiz progress.
- **Components**: The application is divided into several components for better organization:
  - `StartingScreen`: The screen is displayed at the beginning of the quiz.
  - `EndingScreen`: The screen displayed at the end of the quiz, showing the final score.
  - `HighScores`: Displays the high scores achieved by users.
  - `ProgressBar`: A visual indicator of the user's progress through the quiz.
  - `Quiz`: The main component that handles the quiz logic and question display.


 
