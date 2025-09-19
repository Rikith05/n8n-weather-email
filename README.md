🌤️ n8n Daily Weather Email Workflow

This repository contains an automation workflow built with n8n that retrieves daily weather information from the OpenWeatherMap API and delivers it by email using SMTP.

📖 Overview

The workflow is designed for beginners who want to learn n8n by creating a simple but practical project. It demonstrates how to:

Trigger a workflow on a schedule.

Retrieve weather data from a public API.

Transform the data into a formatted email message.

Send the email using Gmail, Outlook, or any SMTP provider.

⚙️ Workflow Components

Schedule Trigger – initiates the workflow at a specific time each day.

HTTP Request – fetches weather data from the OpenWeatherMap API.

Function Node – prepares the email content, including:

Subject line

Plain text body

HTML body (formatted with city, temperature, condition, humidity, and wind speed)

Send Email Node – delivers the weather report to the recipient via SMTP.

🛠️ Prerequisites

n8n https://n8n.io installed locally or on a server.

A free OpenWeatherMap API Key https://openweathermap.org/api

An email account with SMTP access:

Gmail (requires App Password with 2FA enabled).

Outlook or other SMTP-compatible providers.

🔑 Example SMTP Configuration (Gmail)

User: yourname@gmail.com

Password: <Google App Password>

Host: smtp.gmail.com

Port: 465 (SSL) or 587 (TLS)



📧 Example Email Output

Subject: 🌤️ Weather Update for Hyderabad

HTML Body:

🌤️ Weather Update  
City: Hyderabad  
Temperature: 27.2°C  
Condition: haze  
Humidity: 78%  
Wind: 5.1 m/s  

Have a great day! 🌞

📥 Import Instructions

Download or clone this repository.

In n8n, select Import from File and upload Weather-Email-Workflow.json.

Enter your OpenWeatherMap API key and SMTP credentials.

Save and activate the workflow.
