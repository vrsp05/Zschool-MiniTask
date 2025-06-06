# AI-Powered Google Form to Slack Automation

This project demonstrates how to automate a workflow using Make.com, OpenAI (ChatGPT API), Google Forms, and Slack.

## Purpose

This was created as part of an application for Zschool’s AI/ML Automation Internship. The goal was to build a real-world workflow that:

1. Captures a Google Form submission
2. Sends the response to ChatGPT for summarization
3. Posts the summary to a Slack channel

## Tools Used

- [Google Forms](https://forms.google.com) for collecting responses
- [Google Sheets](https://sheets.google.com) to store form submissions
- [Make.com](https://make.com) to create the automation
- [OpenAI API](https://platform.openai.com) for summarizing text using ChatGPT
- [Slack](https://slack.com) for team communication

## How It Works

1. User submits a Google Form
2. Google Sheets captures the submission
3. Make.com watches for new rows and sends the response to OpenAI
4. OpenAI returns a summary
5. Make.com posts the summary in a designated Slack channel

## Screenshots

### 1. Google Form Submission
![Google Form](Google Form Spreadsheet.jpg)

### 2. Make.com Scenario
![Scenario](Make.com Automation.jpg)

### 3. Slack Output
![Slack](Slack AI Message.jpg)

