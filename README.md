# Pokémon GO Data Logger

**A lightweight web tool for Pokémon GO players to log their play sessions, track mobile data usage, and export structured CSV entries for analysis.**

**[Live Version](stantheguy.github.io/pogo-data-logger/)**
---

## 🧠 What It Does

- Lets players fill out a simple form after each play session  
- Automatically formats the data into a CSV row  
- Displays the CSV output for easy copy/paste into Excel, Google Sheets, or other trackers  
- Includes a GPT-style prompt for analyzing logs and optimizing gameplay efficiency

---

## 📦 Features

- Form-based input for session details (gyms, catches, routes, battery, data used, etc.)  
- CSV output with standardized headers  
- Tags and notes for summarizing each trip  
- Built-in prompt for AI models to analyze your logs  
- No login or cloud sync required — everything runs locally

---

## 🚀 Getting Started

1. Clone or download this repo  
2. Open `index.html` in your browser  
3. Fill out the form after each Pokémon GO session  
4. Copy the generated CSV row and paste it into your tracker  
5. Use the included GPT prompt to analyze your data with any AI model

---

## 📊 GPT Prompt for Analysis

You’ll find a copy of the recommended GPT prompt in [`prompt.txt`](./prompt.txt).  
Paste your CSV log and use the prompt to get insights like:
- MB/hour averages  
- Activity-based data usage  
- Bundle recommendations  
- Optimization tips

---

## 🛠️ Contributing

Want to improve the form, add auto-calculations, or build a dashboard?  
Feel free to fork and submit a pull request. Ideas welcome!

---

## 📄 License

MIT License — free to use, remix, and share.

---

## 💬 Why I Made This Tool

As a Pokémon GO player in South Africa, I wanted to understand exactly how much mobile data the game uses during different types of play—especially in areas where data is limited and bundles matter. After manually tracking my own sessions, I realized there was no simple way for other trainers to log their activity and see the patterns. So I built this tool: a lightweight form that turns your play session into a clean CSV entry, ready for analysis or sharing. It’s designed to help players optimize their gameplay, stretch their data bundles, and make smarter decisions—without needing spreadsheets or technical know-how.
