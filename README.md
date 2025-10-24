# Google Sheets → Telegram Automation

## Overview
This automation reads messages from a Google Sheet and automatically posts them to a Telegram chat using a custom bot. It demonstrates integration between Google Cloud APIs and Telegram’s Bot API.

## Tools Used
- Python
- Google Sheets API (`gspread`, `oauth2client`)
- Telegram Bot API (`requests`)
- Jupyter Notebook

## Workflow
1. Message data is entered in a Google Sheet under the column **"Message"**.
2. The Python script authenticates using a service account JSON key.
3. Each message is sent to a Telegram chat using a bot token.
4. The script runs once and stops automatically after sending all messages.

## How to Test
1. Add your own bot token and chat ID in the script.
2. Update your Google Sheet name and credentials path.
3. Run the notebook — messages will appear in Telegram instantly.

## Author
**Akshunn Garg**
