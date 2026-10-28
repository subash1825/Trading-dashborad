# 📈 TradeLog — Trading Journal & Analytics Dashboard

TradeLog is a modern, responsive web application designed for traders to record, track, and analyze their trades. With detailed analytics, interactive charts, and a daily P&L calendar, TradeLog helps you refine your trading edge and maintain discipline.

---

## ✨ Features

- **🔐 Secure Authentication**: Firebase Auth supporting user registration, secure login, password strength meter, and session persistence.
- **📊 Overview Dashboard**: Real-time snapshot of key trading metrics including Total P&L, Win Rate, Profit Factor, Average Trade, and cumulative equity curve powered by Chart.js.
- **📝 Trade Logging (`newtrade.html`)**: Easy and structured entry form for logging trade executions (Ticker, Direction, Entry/Exit prices, Position Size, Stop Loss, Target, Notes, and Tags).
- **📅 P&L Calendar (`calendar.html`)**: Interactive visual calendar displaying daily net gains/losses and trade counts for quick performance evaluation.
- **📜 Trade History (`history.html`)**: Comprehensive, filterable, and searchable log of all past trades with sorting options.
- **📉 Advanced Statistics (`stats.html`)**: In-depth trade analytics, win/loss distributions, risk-to-reward metrics, and drawdown analysis.
- **🌙 Sleek Dark Theme**: Minimalist, high-contrast dark interface tailored for financial market dashboards.

---

## 🛠️ Tech Stack

- **Frontend**: HTML5, CSS3 (Modern Flexbox/CSS Grid), Vanilla JavaScript (ES6+)
- **Charts & Data Visualization**: [Chart.js](https://www.chartjs.org/)
- **Backend & Auth**: [Firebase](https://firebase.google.com/) (Firebase Authentication & Cloud Firestore)
- **Hosting**: Firebase Hosting

---

## 📂 Project Structure

```text
├── index.html          # Authentication (Login & Sign-up page)
├── dashboard.html      # Main dashboard with summary stats and charts
├── newtrade.html       # Trade entry and logging interface
├── calendar.html       # Calendar view of daily P&L performance
├── history.html        # Filterable trade history & detailed trade list
├── stats.html          # Advanced trading metrics & statistical breakdown
├── 404.html            # Custom 404 error page
├── firebase.json       # Firebase Hosting configuration
├── .firebaserc         # Firebase project association
└── .gitignore          # Git ignore rules
```

---

## 🚀 Getting Started

### Prerequisites

- A modern web browser (Chrome, Edge, Firefox, Brave, Safari).
- (Optional) [Firebase CLI](https://firebase.google.com/docs/cli) for deployment.
- (Optional) A local static file server like Live Server (VS Code extension) or `npx serve`.

### Local Setup

1. **Clone the repository**:
   ```bash
   git clone https://github.com/subash1825/Trading-dashborad.git
   cd Trading-dashborad
   ```

2. **Open with a local web server**:
   You can serve the project using any local HTTP server:
   ```bash
   # Using Python
   python -m http.server 8000

   # Or using npx
   npx serve .
   ```
   Open `http://localhost:8000` in your browser.

---

## ☁️ Deployment (Firebase Hosting)

1. Install Firebase CLI globally (if not installed):
   ```bash
   npm install -g firebase-tools
   ```

2. Log in to Firebase:
   ```bash
   firebase login
   ```

3. Deploy to Firebase Hosting:
   ```bash
   firebase deploy
   ```

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to open an issue or submit a pull request.

---

## 📄 License

This project is licensed under the [MIT License](LICENSE) (or your preferred license).
