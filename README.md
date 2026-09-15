# Keyword Caption Bot 🤖📸

A Telegram bot that takes an English keyword and returns a matching image and an Instagram-ready caption — a fully automated pipeline for social media content.

   🎥 **Demo:**

   https://github.com/user-attachments/assets/5bca5a47-85cf-40fa-9757-c966e286edf6

## 🎯 The Problem
Creating consistent, engaging content for Instagram takes time — finding the right image and writing a caption for every post adds up. This bot removes that manual work: send one word, get a ready-to-post image + caption in seconds.

## ⚙️ How It Works
1. Send a keyword to the bot on Telegram
2. The bot fetches a matching image from **Unsplash**
3. **AI** generates a short, creative caption based on the keyword
4. The bot sends back the image and caption, ready to post

## 🧰 Built With
- **n8n** — workflow automation / orchestration
- **Unsplash API** — image sourcing
- **Claude API (Anthropic)** — caption generation
- **Telegram Bot API** — user interface

## 📈 Results / Insights
- Fully automated pipeline — zero manual steps from keyword to finished post
- English-only scope by design, keeping output quality and tone consistent

## 🚀 Setup / How to Run
> Note: this project is kept as a portfolio demo rather than hosted live (to avoid ongoing n8n/hosting costs).
1. Import the `n8n` workflow file from this repo into your own n8n instance
2. Add your own Unsplash API key and Anthropic API key as credentials
3. Connect your Telegram bot token
4. Activate the workflow and message your bot

---
*Built by Shams Asadova*
