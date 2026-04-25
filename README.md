# 💰 WealthTracker / Financial

A high-performance, single-file web application for tracking net wealth trends, recurring income, and personal financial distribution. Built with a "Cyber-Slate" aesthetic, this tool operates entirely on the client side, ensuring privacy and portability.

## 🚀 Overview

**WealthTracker** is designed for users who want a zero-dependency, serverless solution to manage financial data. By leveraging browser `localStorage`, your data stays on your machine, making it a "working without a host" solution that can be deployed instantly via GitHub Pages.

## ✨ Key Features

* **Multi-Member Support:** Manage multiple individuals or accounts within a single dashboard.
* **Recurring Income Simulation:** Configure salaries or recurring expenses with custom start and end dates.
* **Visual Analytics:** * **Net Wealth Trend:** A line chart showing projected growth over 12 months.
    * **Wealth Distribution:** A doughnut chart visualizing the share of wealth per member.
* **One-Time Transactions:** Add specific windfalls or expenses to refine accuracy.
* **Data Portability:** Full **Export** and **Import** functionality (JSON) to move your data between browsers or devices.
* **Privacy First:** No backend, no database, and no tracking. Your financial data never leaves your browser.

## 🛠️ Technical Stack

* **Frontend:** HTML5, CSS3 (CSS Variables for the Cyber-Slate theme).
* **Logic:** Vanilla JavaScript (ES6+).
* **Charts:** Chart.js (via CDN).
* **Storage:** Window.localStorage.

## 📂 Installation & Usage

Since this is a single-file application, there is no installation required.

1.  **Direct Run:** Open `index.html` in any modern web browser.
2.  **GitHub Pages (Recommended):**
    * Push this code to a GitHub repository.
    * Enable **GitHub Pages** in settings.
    * Access your tracker via the provided URL.

## 💾 Data Management

* **Initial Balance:** Set the starting point for each member.
* **Global Start Date:** Define when the wealth simulation begins.
* **Wipe/Reset:** A safety-confirmed option to clear all local data.

## 🎨 Theme: Cyber-Slate
The UI uses a custom palette designed for readability and a modern "slate" feel:
* **Primary:** #3E5B8E (Slate Blue)
* **Accent:** #B69B67 (Gold)
* **Background:** #F8F1E5 (Cream/Parchment)

---
*Developed as a portable, single-file financial utility.*
