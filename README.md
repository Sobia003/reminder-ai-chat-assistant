# Reminder AI Chat Assistant

An AI-powered reminder assistant built with **n8n** and **Google Calendar**. It allows users to create calendar reminders through natural-language chat, making everyday scheduling easier and more convenient.

## Features

- Create reminders through conversational input.
- Interpret reminder dates and times.
- Create events in Google Calendar.
- Handle date and time values using the `Asia/Karachi` timezone.
- Use a one-hour default duration when no duration is specified.

## Workflow Overview

The workflow connects an AI chat assistant with Google Calendar to process reminder requests and create calendar events.

1. Receive a reminder request through chat.
2. Interpret the user's requested reminder details.
3. Process date and time values.
4. Create the corresponding event in Google Calendar.

## Technologies Used

- n8n
- AI Agent
- Google Calendar
- JavaScript / n8n Expressions
- Date and Time Handling

## Setup Instructions

1. Import the workflow JSON into your n8n instance.
2. Configure your own AI model credentials.
3. Connect your Google Calendar account.
4. Select your own Google Calendar.
5. Review the timezone and default duration settings.
6. Test the workflow with a sample reminder before activating it.

## Configuration Notes

- The workflow uses `Asia/Karachi` for timezone handling.
- The default event duration is one hour.
- Credentials and account-specific settings must be configured by each user after importing.
- Make sure your Google Calendar connection has the required permissions.

## Project Purpose

This project demonstrates how AI-powered conversational interfaces can be integrated with workflow automation and calendar services to simplify personal task scheduling.


