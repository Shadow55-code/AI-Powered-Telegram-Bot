# AI-Powered-Telegram-Bot
# 🤖 ShadowAI Bot

ShadowCode is a versatile Telegram bot powered by LLaMA 3 (via Groq API) that helps you solve coding or logic problems, play chess and ludo online, and even evaluate math expressions right from your Telegram chat.

---

## ✨ Features

- 🧠 **AI Problem Solving**: Uses LLaMA 3 through the Groq API to solve technical or logic-based problems.
- ♟️ **Play Chess**: Instantly access online chess via a button.
- 🎲 **Play Ludo**: Start a game of Ludo with one click.
- ➕ **Math Evaluation**: Quickly evaluates simple math expressions.
- 🤖 **Simple and Clean Command Interface**

---

## 🛠️ Commands

| Command       | Description                                      |
|---------------|--------------------------------------------------|
| `/start`      | Welcome message with instructions                |
| `/help`       | List of available commands                       |
| `/solutions`  | Submit a question/problem to solve with AI       |
| `/chess`      | Play chess via an inline button                  |
| `/ludo`       | Play ludo via an inline button                   |

---

## 📦 Requirements

- Python 3.7+
- [pyTelegramBotAPI](https://pypi.org/project/pyTelegramBotAPI/)
- `requests` module

---

## 🚀 Getting Started

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/shadowcode-bot.git
   cd shadowcode-bot
## Install dependencies
pip install -r requirements.txt

## Update your bot token and Groq API key
Token = "YOUR_TELEGRAM_BOT_TOKEN"
GROQ_API_KEY = "YOUR_GROQ_API_KEY"

## Run the bot
python bot.py

