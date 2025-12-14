# 🚀 Quiz Buster: API-Driven Quiz & Quote Generator

A dynamic, dual-feature web application developed as part of the ApexPlanet Web Development Internship. This project demonstrates asynchronous JavaScript programming by integrating multiple external APIs to fetch live data for a technical quiz and a random quote generator.

## 🌟 Live Demo
*(If you are hosting this on GitHub Pages or Vercel, put the link here. Otherwise, you can remove this line)*

## 🎯 Project Overview

This application serves two main purposes:
1.  **Test Technical Knowledge:** Fetches random computer science questions to test the user's programming knowledge.
2.  **Provide Inspiration:** Fetches random insightful quotes for motivation.

The project features a **Professional Dark Mode** UI (Midnight Blue & Electric Cyan) designed for visual comfort and a modern tech aesthetic.

## ✨ Key Features

### 🧠 Live Programming Quiz
* **Dynamic Content:** Questions are fetched in real-time from the **Open Trivia Database**.
* **Category:** Focused specifically on "Computers & Technology."
* **Logic:**
    * Randomized answer shuffling (the correct answer isn't always in the same spot).
    * Instant feedback (Green for Correct / Red for Wrong).
    * Score tracking and final result summary.
    * "Next" button only appears after an answer is chosen to prevent skipping.

### 💬 Random Quote Generator
* **API Integration:** Fetches data from **DummyJSON**.
* **User Interaction:** Button to refresh and fetch a new quote instantly.
* **Loading States:** Includes a spinner to indicate data is being fetched.

### 🎨 UI/UX Design
* **Theme:** Professional Dark Mode (Midnight Blue Background with Neon Cyan accents).
* **Responsiveness:** Fully responsive grid layout that adapts to mobile and desktop screens.
* **Animations:** Smooth hover effects and transitions on cards and buttons.

## 🛠️ Technologies Used

* **HTML5:** Semantic structure.
* **CSS3:** CSS Variables, Flexbox, Grid, and Media Queries for the specific Dark Theme.
* **JavaScript (ES6+):** * `fetch` API for network requests.
    * `async/await` for handling asynchronous data.
    * DOM manipulation for dynamic updates.

## 🔌 APIs Used

1.  **Open Trivia DB:** Used for fetching Computer Science multiple-choice questions.
    * *Endpoint:* `https://opentdb.com/api.php?amount=10&category=18&type=multiple`
2.  **DummyJSON:** Used for fetching random quotes and authors.
    * *Endpoint:* `https://dummyjson.com/quotes/random`

## 🚀 How to Run Locally

1.  **Clone or Download** this repository.
2.  Locate the `index.html` file (or whatever you named the file).
3.  **Double-click** to open it in any modern web browser (Chrome, Edge, Firefox).
    * *Note: An internet connection is required for the APIs to work.*

## 📂 Project Structure

```text
/
├── index.html        # Contains HTML structure, CSS styles, and JS Logic
├── README.md         # Project documentation