# Telegram AI Chatbot with Conversational Memory

## Project Overview

A workshop-based AI chatbot workflow built using n8n, Telegram, and Google Gemini. The workflow receives messages from Telegram, processes them using an AI Agent connected to the Gemini chat model, and sends AI-generated responses back to the user.

It also uses simple session-based memory, with the Telegram chat ID serving as the session key.

## Objectives

- Build a Telegram-based AI chatbot using visual workflow automation.
- Integrate Google Gemini for AI-powered message processing.
- Configure conversational memory using a session identifier.
- Automate incoming message handling and AI-generated replies.

## Technologies Used

- **n8n:** Visual workflow automation
- **Telegram Bot API:** Message input and responses
- **Google Gemini:** AI chat model
- **AI Agent:** Processes incoming messages
- **Simple Memory:** Session-based conversational context

## Workflow

1. **Telegram Trigger:** Receives incoming Telegram messages.
2. **AI Agent:** Processes the user's message and generates a response.
3. **Google Gemini Chat Model:** Provides the language model used by the AI Agent.
4. **Simple Memory:** Uses the Telegram chat ID as the session key.
5. **Send a Text Message:** Sends the generated response back to the Telegram chat.

## Key Features

- Telegram-based conversational interface
- AI-generated responses using Google Gemini
- Session-based memory configuration
- Automated message processing and replies
- Visual workflow orchestration using n8n

## Repository Structure

```text
telegram-ai-chatbot-n8n/
├── README.md
├── workflow.json
├── .gitignore
└── screenshots/
    ├── workflow-overview.png
    └── telegram-chat-demo.png
```

## Prerequisites

- Access to an n8n instance
- A Telegram bot and its credentials
- A Google Gemini API credential
- The exported n8n workflow JSON

## Setup and Usage

1. Open your n8n instance.
2. Import the sanitized `workflow.json` file.
3. Configure your own Telegram and Google Gemini credentials in n8n.
4. Review the workflow connections and settings.
5. Activate the workflow.
6. Send a test message to your Telegram bot.
7. Verify that the chatbot returns an AI-generated response.

## Security

- Never publish API keys, Telegram bot tokens, passwords, or private credentials.
- Use n8n's credential management to store authentication details.
- Inspect exported workflow JSON files before sharing them publicly.
- Do not include private workshop information or credentials in screenshots.

## Project Context

Completed as part of a hands-on workshop focused on AI integration and workflow automation using n8n.

## Learning Outcomes

- Understanding visual workflow automation
- Integrating Telegram with an AI language model
- Configuring AI Agent and chat model nodes
- Setting up session-based memory
- Automating message processing and responses
- Exploring practical AI chatbot integration

## Author

**Boppani Bhargavi**  
Computer Science and Engineering Graduate  
GitHub: [BoppaniBhargavi67](https://github.com/BoppaniBhargavi67)
