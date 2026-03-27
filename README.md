# Stock Lookup Redirector 📈

A lightweight, frontend-only web application designed to streamline stock market research for NSE (National Stock Exchange of India) traders and investors. 

Instead of manually searching for a stock across multiple websites, this tool allows you to enter a stock symbol once and instantly access data across various financial platforms, embed live widgets, and trigger highly-detailed AI analysis prompts.

## 🚀 Features

* **Single Input, Infinite Research:** Type an NSE symbol once and click through to multiple platforms without re-typing.
* **AI-Powered Analysis:** Direct integration with AI tools using pre-configured, highly detailed prompts to instantly generate:
  * Fundamental & Technical Analysis (Bing Chat, Perplexity AI)
  * News & Sentiment Tracking (Positive 🟢, Neutral 🟡, Negative 🔴)
  * Earnings Reports Summaries
* **Embedded Widgets:** View real-time trading widgets and Trendlyne SWOT/Checklist data directly within the UI.
* **Smart Clipboard Workflow:** Includes a one-click "Copy Prompt" feature that copies a comprehensive, structured mega-prompt to your clipboard for use with any AI chatbot (ChatGPT, Claude, etc.).
* **Search History:** Automatically saves your recent searches using browser Local Storage for quick access.
* **Dark Mode UI:** Modern, eye-friendly interface designed for long research sessions.

## 🛠️ Supported Platforms

**Financial Data & Charting:**
* TradingView
* Screener.in
* Yahoo Finance
* Trendlyne
* NSE India Official

**AI & Search Engines:**
* Perplexity AI (General & Finance specific)
* Bing Copilot (Chat & Technical Analysis)
* Google Search (News, Earnings, & Analysis)

## 💻 Installation & Usage

Because this is a vanilla HTML/CSS/JS application, no server or complex installation is required.

1. **Clone the repository:** `git clone https://github.com/yourusername/your-repo-name.git`

2. **Open the file:** Simply double-click `stock look-up.html` to open it in any modern web browser (Chrome, Firefox, Edge, Safari).

3. **Start Searching:** Enter an NSE stock symbol (e.g., `TCS`, `RELIANCE`, `INFY`) and click the search icon or hit Enter. 

4. **Explore:** Click on any of the platform buttons to open a new tab directly to that stock's page, or scroll down to view the embedded widgets.

## 📝 The "Mega-Prompt"

Clicking the "Copy Prompt" button grabs a highly structured prompt designed for AI investment advisors. It commands the AI to break down the stock into 9 categories, including Company Overview, Recent News, Fundamental Analysis, Technical Analysis (RSI, MACD, EMA), Peer Comparison, and a final Short/Long-term verdict. 

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the issues page. If you want to add more platforms or refine the AI prompts, simply fork the repository and submit a pull request.

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).
