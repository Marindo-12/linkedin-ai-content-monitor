# LinkedIn AI Content Monitor

An open-source n8n automation that helps you keep track of interesting LinkedIn posts about Artificial Intelligence, Machine Learning, and Data Science.

## Features

- Monitor LinkedIn email notifications through Gmail.
- Filter posts by configurable technology topics.
- Extract available post text, author information, and original links.
- Avoid processing duplicate notifications.
- Organize matching posts into a daily digest.
- Send the digest by email with a ZIP archive.

## Default Topics

- Artificial Intelligence
- Machine Learning
- Data Science
- Deep Learning
- Large Language Models (LLMs)
- Data Engineering

## Architecture

Gmail Trigger → Notification Filter → Content Extraction → Topic Classification → Deduplication → Daily Digest → ZIP Archive → Gmail

## Requirements

- Docker Desktop
- n8n Community Edition
- Gmail account
- LinkedIn email notifications enabled

## Important limitations

This project uses LinkedIn notifications delivered to Gmail. It does not scrape LinkedIn or bypass LinkedIn API permissions.

The available text, links, and images depend on what LinkedIn includes in each notification. Full post content and images are not guaranteed.

## Installation

Installation instructions and the n8n workflow export will be added as the project develops.

## Privacy and security

- Never commit passwords, API keys, OAuth tokens, or credentials.
- Keep n8n credentials inside n8n's credential manager.
- Respect LinkedIn's terms and the original authors' content rights.

## License

MIT
