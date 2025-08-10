# Daily Business Insights Bot – n8n Workflow

## 📌 Overview
This is a free n8n automation that sends you a short AI-generated summary of your business performance every morning.

## ✨ Features
- Fetch data from Google Sheets (or any connected data source)
- Summarize using AI (OpenAI or Google Gemini)
- Deliver insights via Telegram or WhatsApp
- Runs automatically every morning at 8:00 AM IST

## 📦 Requirements
- n8n (self-hosted or cloud)
- Google Sheets API credentials
- OpenAI or Google Gemini API key
- Telegram Bot token (or WhatsApp Cloud API credentials)

## 🚀 Setup Instructions
1. Import the provided `daily_insights_bot.json` into your n8n instance.
2. Connect your credentials for Google Sheets, AI API, and Telegram/WhatsApp.
3. Update the Google Sheet ID, chat IDs, and credential names in the nodes.
4. Activate the workflow.

## 📷 Example
This bot will send you messages like:
