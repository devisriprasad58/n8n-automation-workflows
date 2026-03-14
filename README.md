# n8n Automation Workflows Portfolio

This repository contains automation workflows built using **n8n** demonstrating API integrations, scheduled automations, webhook triggers, and Telegram bot notifications.

These workflows simulate real-world automation use cases such as monitoring APIs, sending alerts, and capturing leads.

---

## 1. API → Telegram Alert

Fetches data from an external API and sends automated alerts via a Telegram bot.

**Workflow:**

Schedule Trigger → HTTP Request → JavaScript → Telegram

**Use Case:**
Monitor API responses and notify users instantly.

---

## 2. Website Monitor Automation

Periodically checks website content and sends updates through Telegram.

**Workflow:**

Schedule Trigger → HTTP Request → JavaScript Processing → Telegram Notification

**Use Case:**
Monitor website changes or content updates.

---

## 3. Bitcoin Price Alert Bot

Fetches cryptocurrency price data from an external API and sends automatic price alerts.

**Workflow:**

Schedule Trigger → HTTP Request → Data Processing (JavaScript) → Telegram Alert

**Use Case:**
Track cryptocurrency prices and receive automated updates.

---

## 4. Lead Notification Automation

Receives lead data through a webhook and sends instant alerts via Telegram.

**Workflow:**

Webhook → JavaScript → Telegram

**Use Case:**
Capture leads from forms or APIs and notify marketing teams in real time.

---

## Tech Stack

* n8n (Workflow Automation)
* JavaScript
* HTTP APIs
* Telegram Bot API
