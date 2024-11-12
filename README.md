# 🚀 ReactiveInvestor - Finance Tracker
 A slick React + .NET Core project to keep tabs on the stock market, securities, and cryptocurrencies in real-time using Financial Modeling Prep API. Build and manage your portfolio with mathematical precision and forecasting. All user interactions and portfolios are securely stored in an SQLEXPRESS database with encrypted connections. Frontend crafted with TypeScript and React (TSX), styled using Tailwind CSS; backend powered by .NET Core C#.

### 🛠 Tech Stack
- React (TypeScript)
- Tailwind CSS
Backend:
- .NET Core (C#)
Database:
- SQLEXPRESS
APIs:
- Financial Modeling Prep API
### 📖 Features
- Real-Time Market Tracking: Keep up with live updates on stocks, securities, and crypto.
- Portfolio Management: Calculate and assemble your custom portfolio using advanced math and forecasting algorithms.
- User Operations Logging: All user interactions are recorded and stored securely.
- Secure Connections: All data transmissions are encrypted for maximum security.
### 🚀 Getting Started
- Prerequisites
- Node.js (v14 or later)
- .NET Core SDK (v5.0 or later)
- SQLEXPRESS installed and configured
- npm or yarn
### 🔧 Installation
- Clone the repo:
bash
`git clone https://github.com/yourusername/finance-tracker.git`
- register and receive your unique token on the website:`https://site.financialmodelingprep.com/`
### ⚙️ Configuration
- Create a .env file in the frontend directory.
- Add your API keys and necessary environment variables.
- REACT_APP_API_BASE_URL=http://localhost:5000/api
- REACT_APP_FINANCIAL_MODELING_PREP_API_KEY=your_api_key_here
Backend:
- Update appsettings.json with your database connection string and other settings.
{
  "ConnectionStrings": {
    "DefaultConnection": "Server=localhost;Database=FinanceTracker;Trusted_Connection=True;"
  },
  "ApiKeys": {
    "FinancialModelingPrep": "your_api_key_here"
  }
}
### 🏃 Running the App
npm start or yarn start
The frontend should now be running at http://localhost:3000 and the backend API at http://localhost:5000.
### 🛡 Security
All API calls and database connections are secured using industry-standard encryption protocols.
Sensitive data like API keys and database passwords are stored in environment variables and configuration files not checked into source control.
### 📄 License
This project is licensed under the MIT License - see the LICENSE file for details.
