# Telegram Chatbot

A simple Telegram chatbot built using Python, Aiogram, and OpenAI.

The bot receives messages from Telegram users and generates responses using OpenAI.

## Features

* Telegram bot integration
* AI-powered responses using OpenAI
* Asynchronous message handling
* Environment variables for API keys and bot token

## Bot

**Bot:** @letschat05_bot

## Tech Stack

* Python
* Aiogram
* OpenAI API
* python-dotenv

## Project Structure

```text
Telegram-Chatbot/
├── bot.py
├── requirements.txt
├── .env.example
├── .gitignore
└── README.md
```

## Setup

### 1. Clone the repository

```bash
git clone <your-repository-url>
cd Telegram-Chatbot
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Configure environment variables

Create a `.env` file in the project root:

```env
OPENAI_API_KEY=your_openai_api_key_here
TELEGRAM_BOT_TOKEN=your_telegram_bot_token_here
```

You can use `.env.example` as a reference.

**Do not upload the `.env` file to GitHub.**

### 4. Run the bot

```bash
python bot.py
```

The bot will start listening for messages on Telegram.

## Example

Send a message to:

**@letschat05_bot**

and the chatbot will generate an AI response.

## Disclaimer

This project is created for learning and demonstration purposes.
