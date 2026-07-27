# 📰 News App — Daily News Web Application

A responsive **News Web Application** built using **HTML, CSS, and JavaScript** that allows users to explore daily news across multiple categories, search for specific topics, save interesting articles to a watchlist, and switch between light and dark themes.

The project focuses on **API integration, asynchronous JavaScript, DOM manipulation, local storage, and responsive frontend development**.

## 🚀 Features

### 📰 Daily News

Fetches and displays the latest news articles from a news API, helping users stay updated with current events.

### 🔍 Search News

Users can search for news using keywords or topics through the search bar.

Examples:

* Artificial Intelligence
* Stock Market
* Cricket
* Space
* Technology

### 📂 News Categories

Users can quickly explore news from different categories using category buttons such as:

**Sports | Technology | Business | Entertainment | Health | Science**

Clicking a category dynamically fetches and displays news related to that topic.

### ⭐ Watchlist

Users can save interesting news articles to their **watchlist** and access them later.

The watchlist uses browser storage to preserve saved articles without requiring a user account.

### 🌙 Light & Dark Mode

Includes a theme toggle that allows users to switch between **Light Mode** and **Dark Mode** for a better viewing experience.

### 📱 Responsive Design

The interface is designed to work across different screen sizes, including desktop, tablet, and mobile devices.

---

## 🛠️ Tech Stack

| Technology    | Purpose                                 |
| ------------- | --------------------------------------- |
| HTML5         | Structure and content                   |
| CSS3          | Styling and responsive design           |
| JavaScript    | Application logic and interactivity     |
| REST API      | Fetching real-time news                 |
| Local Storage | Storing watchlist data                  |
| Git & GitHub  | Version control and source code hosting |

---

## ⚙️ How It Works

The application fetches news from an external **News API** using JavaScript.

When the user selects a category:

`Category → API Request → Fetch News → Process Response → Display Articles`

When the user searches for a topic:

`Search Query → API Request → Fetch Matching News → Display Results`

JavaScript dynamically updates the page without requiring a full page reload.

---

## 📁 Project Structure

```text
news-app/
│
├── index.html
├── style.css
├── script.js
├── README.md
└── assets/
    └── images/
```

The exact structure may vary depending on the implementation.

---

## 💻 Getting Started

### 1. Clone the repository

```bash
git clone <your-github-repository-url>
```

### 2. Open the project

```bash
cd news-app
```

### 3. Run the application

Open `index.html` directly in your browser or use a development server such as **Live Server** in VS Code.

If the application uses an API key, configure the required API key before running the project.

---

## 🎯 Key Concepts Demonstrated

This project demonstrates practical frontend development concepts including:

* Fetch API and asynchronous JavaScript
* REST API integration
* DOM manipulation
* Event handling
* Search functionality
* Dynamic content rendering
* Local Storage
* Theme management
* Responsive web design
* Error handling for API requests

---

## 🔮 Future Improvements

Possible improvements include:

* Pagination or infinite scrolling
* News filtering by country or language
* Trending news section
* Article sorting
* Improved watchlist management
* Loading indicators and skeleton screens
* Backend integration for secure API key handling
* User authentication and cloud-based saved articles

---

## 📸 Screenshots

Add screenshots of the application here.

```text
Home Page
[Add Screenshot]

Dark Mode
[Add Screenshot]

Search Results
[Add Screenshot]

Watchlist
[Add Screenshot]
```

---

## 👨‍💻 Author

**P. Anvesh Reddy**

GitHub: `Anveshreddy2006`

---

## ⭐ Support

If you found this project useful or interesting, consider giving the repository a ⭐.
