# React News App

A modern, responsive news application built with **React JS** and **Bootstrap**. This project fetches and displays real-time headlines using the NewsAPI.

## 📱 Project Overview
This app provides a clean interface for browsing news across different categories. It demonstrates how to handle API integration, manage component states, and secure sensitive data in a React environment.

## 🛠️ Features
- **Live News Feed:** Real-time data fetching from NewsAPI.org.
- **Category Navigation:** Switch between Business, Tech, Sports, and more.
- **Responsive Layout:** Fully optimized for mobile and desktop using Bootstrap components.
- **Secure Architecture:** Uses Vite environment variables to protect API keys.

## 🧰 Tech Stack
- **Framework:** React (Vite)
- **Styling:** Bootstrap 5
- **Data Source:** NewsAPI

## 🔒 Security & Configuration
To keep the project secure, the API key is stored in a `.env` file using the variable name `VITE_API_KEY`. This file is excluded from version control via `.gitignore` to prevent unauthorized access to the API credentials.

---
*Built as part of a React development journey.*