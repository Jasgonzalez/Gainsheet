# 💪 Gain Sheet

**Gain Sheet** is a smart, user-friendly workout tracking app that connects directly to your **Google Spreadsheet**, making it easy to log sets, reps, weights, and track your progress over time.

## 📋 Overview

Tired of clunky workout apps or forgetting your progress at the gym? Gain Sheet gives you a clean and simple interface to log your workouts, while storing your data in a connected Google Sheet for easy access, analysis, and visualization.

Whether you're lifting heavy, doing bodyweight exercises, or following a custom routine — Gain Sheet helps you stay consistent and informed.

## ⚙️ Features

- 📝 **Log Reps, Sets, and Weights**  
  Easily record your workout details in real-time.

- 🔗 **Google Sheets Integration**  
  Data is stored securely in your personal spreadsheet.

- 📈 **Progress Tracking**  
  View weekly/monthly summaries of your gains.

- 🔔 **Workout Reminders** *(optional)*  
  Set notifications to never miss a lift.

- 🧠 **Smart Suggestions** *(in development)*  
  Auto-fill your last session’s weights to help you progress.

## 🚀 Tech Stack

- **Frontend**: React  
- **Backend**: Flask + Python  
- **Database**: Google Sheets API  
- **Auth**: Google OAuth 2.0  
- **Cloud**: Optional hosting with Vercel / Heroku

## 📦 Getting Started

### Prerequisites

- Node.js v18+  
- Python 3.10+  
- Google Cloud project with Sheets API enabled  
- A Google Sheet prepared for data logging

### Installation

#### Frontend

```bash
cd gain-sheet-frontend
npm install
npm run dev
