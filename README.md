# User API React Application

A React application that retrieves user information from a REST API and displays it in a clean, structured table. The project demonstrates API integration using React Hooks, including `useState()` and `useEffect()`, along with loading and error handling.

## 🚀 Live Demo

**[View Live Demo](https://muthukoornandini.github.io/users-api-react/)**

## 📌 Project Overview

This application fetches user information from the JSONPlaceholder REST API and dynamically displays the retrieved data.

The application provides:

* User ID
* Name
* Username
* Email
* Loading state while data is being retrieved
* Error handling when the API request fails

## 🛠️ Technologies Used

* React
* JavaScript
* Vite
* React Hooks
* REST API
* HTML
* CSS
* Git & GitHub
* GitHub Pages

## 🔗 API Used

The application retrieves data from:

**JSONPlaceholder Users API**

`https://jsonplaceholder.typicode.com/users`

## ⚙️ React Concepts Demonstrated

### useState()

Used to store:

* User information
* Loading status
* Error messages

### useEffect()

Used to execute the API request when the component is loaded.

### fetch()

Used to retrieve user information from the REST API.

## 📊 Application Flow

```text
React Application
       ↓
   useEffect()
       ↓
     fetch()
       ↓
JSONPlaceholder API
       ↓
   User Data
       ↓
    useState()
       ↓
 User List Table
```

## 📋 Features

* Fetches user data from an external API
* Displays users dynamically
* Shows `Loading...` while the request is in progress
* Displays an error message if the request fails
* Responsive React-based structure
* Deployed using GitHub Pages

## 💻 Run Locally

Clone the repository:

```bash
git clone https://github.com/muthukoornandini/users-api-react.git
```

Navigate to the project folder:

```bash
cd users-api-react
```

Install dependencies:

```bash
npm install
```

Start the development server:

```bash
npm run dev
```

Open the local URL shown in the terminal.

## 📁 Project Structure

```text
users-api-react/
│
├── public/
├── src/
│   ├── assets/
│   ├── App.jsx
│   ├── App.css
│   ├── Users.jsx
│   ├── index.css
│   └── main.jsx
│
├── index.html
├── package.json
├── vite.config.js
└── README.md
```

## 🌐 Deployment

The application is deployed using **GitHub Pages**.

### Live Application

**https://muthukoornandini.github.io/users-api-react/**

## 🎯 Learning Outcome

This project provides practical experience in:

* Building React components
* Managing component state
* Using React Hooks
* Calling REST APIs
* Handling asynchronous data
* Displaying API data dynamically
* Implementing loading and error states
* Deploying a React application

## 👩‍💻 Author

**Muthukoornandini**

GitHub: **[muthukoornandini](https://github.com/muthukoornandini)**
