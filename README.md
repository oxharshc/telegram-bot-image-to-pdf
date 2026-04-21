# 📸➡️📄 Telegram Image to PDF Bot

A simple bot that converts images to PDFs right in your Telegram chats!

## 🚀 Getting Started

### 1️⃣ Prerequisites
- Python 3.6 or higher
- Telegram account
- Basic terminal knowledge

### 2️⃣ Installation Guide

#### Step 1: Download the bot files
Download or clone this repository to your computer.

#### Step 2: Set up Python environment
```bash
# Create a virtual environment
python -m venv venv

# Activate it
# Windows:
.\venv\Scripts\activate
# Mac/Linux:
source venv/bin/activate
```

#### Step 3: Install required packages
```bash
pip install -r requirements.txt
```

### 3️⃣ Bot Setup

#### Step 1: Get Telegram API credentials
1. Go to https://my.telegram.org/apps
2. Create an application
3. Note down your:
   - API ID
   - API Hash
   - Bot Token (get this from @BotFather)

#### Step 2: Configure the bot
Then you can type, file in the project folder with:
```
copy .env.example .env
```
you will see this in `.env` file
```
API_ID=your_api_id_here
API_HASH=your_api_hash_here
BOT_TOKEN=your_bot_token_here
```

### 4️⃣ Running the Bot
```bash
python telegram_img_to_pdf.py
```

## 🤖 How to Use
1. Start a chat with your bot in Telegram
2. Send `/start` to see available commands
3. Send images to the bot
4. Use `/convert` to make a PDF
5. Use `/clear` to reset your images and stats

## 🔍 Features
- Convert single or multiple images to PDF
- View your usage statistics with `/usage`
- Admin can check bot stats with `/stats`
- Simple and easy to use!

## ❓ Need Help?
If you get stuck:
1. Make sure all dependencies are installed
2. Double-check your API credentials
3. The bot must be running to respond to messages

⚠️ **Important Security Note** ⚠️
Never share your `.env` file or API credentials with anyone!
