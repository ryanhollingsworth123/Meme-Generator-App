# Meme Generator App

**A React + Vite meme generator that fetches random meme templates from the Imgflip API and lets you add custom top & bottom text.**  
This project was built to practice handling side effects with `useEffect`, fetching data from an external API, and interactive UI updates.

---

## Live Demo

Try the app live here:  
https://ryanhollingsworth123.github.io/Meme-Generator-App/

---

## Project Overview

The Meme Generator App:

- Fetches **random meme images** from the Imgflip API.
- Lets users **input top and bottom text**.
- Displays a **preview meme image** with the custom captions.
- Demonstrates the use of **React hooks** (`useState`, `useEffect`) and **fetch requests** to external APIs.

---

## Tech Stack

- **React** — UI & state management  
- **Vite** — Fast dev build tooling  
- **JavaScript (ES6+)** — Core language features  
- **CSS** — Styling  
- **npm** — Package management  
- **Imgflip API** — Random meme templates source

---

## Project Structure

Meme-Generator-App/
├── public/ # Static files & HTML
├── src/ # React source files
│ ├── App.jsx # Main component & game logic
│ ├── index.jsx # Entry point
│ └── assets/ # Images or static assets
├── .gitignore
├── index.html
├── package.json # Scripts & dependencies
├── vite.config.js # Vite configuration
└── README.md

---

## Installation & Local Setup

Follow these steps to run the project locally:

1. **Clone the repository**
   ```bash
   git clone https://github.com/ryanhollingsworth123/Meme-Generator-App.git
Change into the project directory

cd Meme-Generator-App
Install the dependencies

npm install
Start the development server

npm run dev
Open in your browser

http://localhost:5173/

**How It Works**

On load, the app fetches a list of meme templates from the Imgflip API.

When the user clicks “Get new meme image”, the app selects a random meme template.

Users type in Top Text and Bottom Text.

The meme image updates in real time with the custom text overlay.

This workflow demonstrates React state updates, side effects, and event handling.
