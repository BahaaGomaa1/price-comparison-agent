# AI Product Price Comparison Agent

An AI-powered product price comparison agent built with **Python and LangChain**.

The agent can search the web for product prices, verify available offers, compare prices, and deliver the results through **Telegram** or **Email**.

## 🚀 Features

* 🔎 Web search for product prices
* 🤖 AI-powered product analysis
* 💰 Compare prices from different sources
* 📅 Track the date when prices were checked
* 📱 Send price reports through Telegram
* 📧 Send professional price reports by Email
* 🛠️ LangChain tool calling
* 🔐 Environment variables for API keys and credentials

## 🧠 How It Works

The user sends a request such as:

> Check the price of the iPhone 12 Pro in Egypt and send the report to Telegram.

The AI agent then:

1. Understands the user's request.
2. Gets the current date and time.
3. Searches the web for product prices.
4. Checks different offers and sources.
5. Compares the available prices.
6. Generates a clear price comparison report.
7. Sends the report through Telegram or Email when requested.

## 🏗️ Architecture

```text
User
  ↓
AI Agent
  ↓
Tool Calling
  ├── Web Search
  ├── Date & Time
  ├── Telegram
  └── Email
  ↓
Price Comparison Report
```

## 🛠️ Technologies

* Python
* LangChain
* LangGraph
* Tavily Search
* OpenRouter / LLM
* Telegram Bot API
* Gmail SMTP
* python-dotenv
* Requests

## 📁 Project Structure

```text
price-comparison-agent/
│
├── price_comparison_agent.ipynb
├── .gitignore
├── requirements.txt
└── README.md
```

## 🔑 Environment Variables

Create a `.env` file in the project directory:

```env
OPENROUTER_API_KEY=your_api_key
TAVILY_API_KEY=your_api_key

TELEGRAM_BOT_TOKEN=your_bot_token
TELEGRAM_CHAT_ID=your_chat_id

SENDER_EMAIL=your_email
SENDER_PASSWORD=your_app_password
```

> Never upload your `.env` file or expose API keys and passwords publicly.

## 📦 Installation

Clone the repository:

```bash
git clone https://github.com/bahaagomaa1/price-comparison-agent.git
cd price-comparison-agent
```

Install the required packages:

```bash
pip install -r requirements.txt
```

Create your `.env` file and add the required credentials.

Then open:

```text
price_comparison_agent.ipynb
```

and run the notebook.

## 💬 Example

User:

```text
Check the price of the iPhone 12 Pro in Egypt.
Send the report to my Telegram.
Also email the report to my email.
```

The agent searches for available prices, compares the results, and sends the generated report through the requested channels.

## 🎯 Project Goals

This project was built to practice and demonstrate:

* Building AI agents with Python
* LangChain tool calling
* LLM integration
* Web search integration
* API integration
* Telegram automation
* Email automation
* Environment variable management
* Building practical AI automation workflows

## 🔮 Future Improvements

* Add more e-commerce sources
* Improve product matching and variant detection
* Add historical price tracking
* Store price history in a database
* Add scheduled price monitoring
* Add price-drop alerts
* Build a web interface
* Add more communication channels

## 👨‍💻 Author

**Bahaa Gomaa**

AI Automation & AI Agents Developer

Interested in building practical AI agents, automation systems, and intelligent workflows with Python, LangChain, APIs, and AI tools.
