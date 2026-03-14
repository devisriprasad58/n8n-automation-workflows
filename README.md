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

## Tech Stack

* n8n
* JavaScript
* HTTP APIs
* Telegram Bot API
