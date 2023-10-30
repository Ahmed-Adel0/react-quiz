# React Quiz App

## Description

This is a React-based quiz app that allows users to take a quiz, answer questions, and keep track of their score. The app includes various features, such as a countdown timer, a highscore, and a structured interface to create an engaging quiz experience.

## Table of Contents

- [Features](#features)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [State Management](#state-management)
- [API Integration](#api-integration)

## Features

- Interactive quiz experience with countdown timer.
- Score tracking and highscore comparison.
- Error handling for data fetching.
- Modular component structure for easy maintenance.
- Real-world scenario to practice React skills.

## Project Structure

The project is structured into different components, each responsible for a specific part of the application. This modularization enhances maintainability and understanding.

- `Header`: The top navigation/header component.
- `MainSection`: The main content area of the app.
- `Loader`: Displayed while data is being fetched.
- `Error`: Shown in case of data fetching errors.
- `StartScreen`: The initial screen before starting the quiz.
- `Question`: Component responsible for rendering questions.
- `NextButton`: Handles moving to the next question.
- `Progress`: Displays the user's progress and score.
- `FinishScreen`: Shown when the quiz is completed.
- `Footer`: The app's footer component.
- `Timer`: Manages the countdown timer.

## State Management

The app uses the `useReducer` hook for state management. The state is initialized in the `App` component and updated through actions dispatched by the `reducer` function.

## API Integration

The app fetches quiz questions from a local server. The endpoint used for fetching questions is `http://localhost:9000/questions`. Error handling is implemented for scenarios where data retrieval fails.
