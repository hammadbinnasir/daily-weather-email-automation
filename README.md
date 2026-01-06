# Daily AI-Powered Weather Email Automation

This project is an automated workflow that sends a daily weather report via email using AI-generated summaries.

## Overview
The workflow runs automatically every morning and:
- Fetches live weather data from OpenWeatherMap
- Uses an AI model to generate a readable summary
- Sends the report via email using Gmail
- Runs fully automated using n8n

## Tech Stack
- n8n (Workflow Automation)
- OpenWeatherMap API
- Gemini Chat Model
- Gmail API / SMTP

## Workflow Steps
1. Scheduled trigger (daily)
2. Fetch weather data via API
3. Generate AI-based summary
4. Send formatted email

## Screenshots
Screenshots of the workflow and email output are included in the `/screenshots` folder.

## Environment Variables
Sensitive values are excluded. Create a `.env` file using the template below.

