# React Quiz Application

This is a React-based quiz app that allows users to take a quiz, answer questions, and keep track of their score.
The app includes various features, such as a countdown timer, a high score, and a structured interface to create an engaging quiz experience.

## Table of Contents

- [Description](#description)
- [Features](#features)
- [State Management](#state-management)
- [API Integration](#api-integration)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)

## Description

This React-based quiz application provides users with an interactive platform to participate in quizzes and test their knowledge.
Users can experience a feature-rich environment with a countdown timer, progress tracking, and high score recording.
The structured interface ensures a seamless and engaging quiz-taking experience.

## Features

- User-friendly interface for quiz participation.
- Dynamic rendering of questions and progress tracking.
- Timer functionality for time-limited questions.
- Start, pause, and finish states for a complete quiz experience.
- High score tracking for users.

## State Management

In this version, we made significant changes and improvements to enhance the application's structure, maintainability, and user experience:

1. **State Management Refactor:**

   - Introduced the `QuizContext` to manage the quiz state, eliminating prop drilling.
   - Utilized the `useQuiz` hook to access the quiz state within components.

2. **Simplified Component Hierarchy:**

   - Removed the need for passing props through multiple layers.
   - Cleaned up the `App` component, making it more focused on rendering components based on quiz status.

3. **Context Abstraction:**

   - Abstracted away fetch and dispatch logic into the `QuizContext` or associated provider component.

4. **Improved Readability:**
   - Simplified the rendering logic based on the quiz status for better code readability.

## API Integration

The application integrates with an API to fetch quiz questions dynamically. The API endpoint is specified in the `useEffect` hook within the `App` component.

## Technologies Used

- React
- React Context API
- JavaScript (ES6+)
