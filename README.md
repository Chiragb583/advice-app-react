# Advice App

A simple React web application that fetches and displays random pieces of advice using an external API.

The project was created to practice **React fundamentals**, API requests, state management, event handling, and working with asynchronous data.

## 🚀 Live Demo

heroic-dusk-656bd8.netlify.app

## 📸 Preview

[Advice App Preview](./preview.png)

## ✨ Features

* Fetches random advice from an external API
* Displays the advice dynamically on the screen
* Generates new advice when the user clicks the button
* Handles API requests using Axios
* Uses React state to update the UI
* Responsive and simple user interface

## 🛠️ Technologies Used

* **React** – Frontend library
* **Vite** – Development and build tool
* **JavaScript (ES6+)**
* **Axios** – Making API requests
* **CSS / Tailwind CSS** – Styling
* **ESLint** – Code linting

## 📂 Project Structure

```text
Advice_Project/
│
├── public/
│
├── src/
│   ├── App.jsx
│   ├── App.css
│   ├── index.css
│   └── main.jsx
│
├── .gitignore
├── eslint.config.js
├── index.html
├── package.json
├── package-lock.json
├── vite.config.js
└── README.md
```

## ⚙️ Getting Started

Follow these steps to run the project locally.

### 1. Clone the repository

```bash
git clone https://github.com/Chiragb583/advice-app-react.git
```

### 2. Navigate to the project directory

```bash
cd advice-app-react
```

### 3. Install dependencies

```bash
npm install
```

### 4. Start the development server

```bash
npm run dev
```

Vite will provide a local URL, usually:

```text
http://localhost:5173
```

Open the URL in your browser to view the application.

## 🔌 API

This application uses the **Advice Slip API** to retrieve random advice.

API endpoint:

```text
https://api.adviceslip.com/advice
```

Each request returns an advice object containing an ID and the advice text.

Example response:

```json
{
  "slip": {
    "id": 42,
    "advice": "Anything worth doing is worth doing slowly."
  }
}
```

## 🧠 What I Learned

While building this project, I practiced:

* Creating React components
* Using `useState`
* Handling button click events
* Making API requests with Axios
* Working with asynchronous JavaScript
* Updating the UI when state changes
* Handling API responses
* Setting up a React project with Vite
* Using Git and GitHub for version control

## 🔮 Future Improvements

Some features that could be added in the future:

* Add a loading indicator while fetching advice
* Add error handling when the API request fails
* Add a button to copy advice to the clipboard
* Add the ability to share advice
* Add animations when new advice appears
* Improve mobile responsiveness
* Add dark/light mode

## 📄 License

This project is created for learning and practice purposes.
