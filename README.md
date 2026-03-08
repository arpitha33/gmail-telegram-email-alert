# Gmail → Telegram Email Alert Automation
This project is an automation workflow built using **n8n** that sends instant Telegram notifications whenever a new email arrives in Gmail.

## Features

* Monitors Gmail inbox
* Detects new emails automatically
* Sends instant alerts to Telegram
* Displays sender and subject in the notification

## Workflow Architecture

Gmail Trigger → n8n Automation → Telegram Bot Notification

## Technologies Used

* n8n
* Gmail API
* Telegram Bot API

## Setup

1. Import the workflow JSON file into n8n
2. Configure Gmail credentials
3. Create a Telegram bot using BotFather
4. Add your Telegram chat ID
5. Activate the workflow

## Example Notification

📩 New Email Received
From: [sender@example.com](mailto:sender@example.com)
Subject: Meeting Tomorrow
