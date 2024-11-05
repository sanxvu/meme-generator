# Meme Generator

## Description
The Meme Generator is an interactive web app built with React that allows users to generate memes by selecting images and adding custom text. It demonstrates key React concepts such as event listeners, state management, conditional rendering, user input via forms, and side effects using useEffect. The app fetches memes from an API and lets users customize them before sharing.

## Features
- **Interactive Web App**: Users can select a meme template and add custom top and bottom text to generate personalized memes.
- **Event Listeners**: The app listens for user interactions (e.g., button clicks) to update the state and generate new memes.
- **State Management**: The app uses React's useState hook to track the current meme template, user input, and generated meme.
- **Conditional Rendering**: Displays different parts of the UI based on the state (e.g., showing meme templates or the generated meme).
- **Side Effects with useEffect**: The app fetches a list of meme templates from an API using useEffect when the component mounts.

## Technologies Used
- **React**: For building the user interface.
- **JavaScript**: For handling logic and user interactions.
- **HTML/CSS**: For the app layout and styling.