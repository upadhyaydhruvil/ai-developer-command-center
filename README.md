# AI Developer Command Center

An automated AI-powered developer news briefing system built with n8n.

The workflow collects developer and AI-related content, filters relevant articles, generates a concise daily brief using an AI model, and delivers the final report directly to Telegram.

## Workflow

Schedule Trigger
→ Fetch Developer News
→ JavaScript Processing
→ HTTP Request
→ Filter Relevant Content
→ Limit Articles
→ Format Data
→ AI Summarization
→ JavaScript Processing
→ Telegram

## Features

- Automated daily developer news collection
- AI-powered article summarization
- Relevance filtering
- Top article selection
- Developer-focused insights
- Automated Telegram delivery
- Fully automated n8n workflow

## Tech Stack

- n8n
- JavaScript
- HTTP APIs
- AI / LLM
- Telegram Bot API
- GitHub
- Docker

## Example Output

The system generates a daily brief containing:

1. Important developer/AI articles
2. Short summaries
3. Why developers should care
4. Article URLs
5. Top developer takeaways

## Project Structure

```text
ai-developer-command-center/
├── workflows/
│   └── AI Developer Daily Brief.json
├── .gitignore
└── README.md
