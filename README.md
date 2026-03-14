# n8n Automation Workflows Portfolio

This repository contains automation workflows built using n8n involving API integrations, scheduled triggers, and Telegram bot notifications.

## 1. API → Telegram Alert

Workflow that fetches external API data and sends automated alerts via Telegram bot.

Flow:
Schedule Trigger → HTTP Request → JavaScript → Telegram

## 2. Website Monitor Automation

Checks a website periodically and sends updates through Telegram.

Flow:
Schedule Trigger → HTTP Request → JavaScript Processing → Telegram Notification

## 3. Bitcoin Price Alert Bot

Fetches cryptocurrency price data from an external API and automatically sends price updates via Telegram bot.

Flow:
Schedule Trigger → HTTP Request → Data Processing (JavaScript) → Telegram Alert
4. Lead Notification Automation

Webhook → JavaScript → Telegram

Description:
This workflow receives lead data through a webhook, processes the information using JavaScript, and sends an instant notification through a Telegram bot. This can be used by marketing teams to get real-time alerts whenever a new lead is generated.

## Tech Stack

* n8n
* JavaScript
* HTTP APIs
* Telegram Bot API
