🌤️ n8n Daily Weather Email Workflow

This project is an automation built in n8n that fetches the daily weather using the OpenWeatherMap API and sends it as an email via SMTP (Gmail/Outlook).

🚀 Features

Runs automatically every day at a scheduled time (via Schedule Trigger)

Fetches live weather data for a chosen city (via HTTP Request to OpenWeatherMap)

Formats the weather into a clean email with subject + HTML body (via Function Node)

Sends the weather email to your inbox (via Send Email Node)

🛠️ Workflow Nodes

Schedule Trigger → Runs daily at 8:00 AM

HTTP Request → Calls OpenWeatherMap API with your city + API key

Function Node → Creates subject, text, and html email content (includes humidity + wind)

Send Email → Sends the email through Gmail/Outlook SMTP

📦 Requirements

n8n
