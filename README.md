# AI WhatsApp Support Agent

An AI-powered WhatsApp customer support automation built around n8n workflows. It receives customer messages, prepares structured input, uses AI to classify the request, determines priority, drafts a helpful reply, and supports human escalation.

## Workflow

**WhatsApp Message → Webhook → Prepare Message → AI Classification → Response → Human Escalation**

## Features

- AI-powered customer support
- WhatsApp webhook integration concept
- Intent classification
- Priority detection
- Message summarization
- Automated reply generation
- Human-agent escalation
- Structured JSON output
- Reusable AI prompt configuration
- Secure example configuration

## Supported Intents

- Product Inquiry
- Order Status
- Technical Support
- Billing
- Complaint
- Feedback
- General Question
- Human Agent Request

## Project Structure

```text
AI-WhatsApp-Support-Agent/
├── workflow/
│   └── whatsapp-support.json
├── prompts/
│   └── support-agent.json
├── config/
│   └── example.json
├── data/
│   └── intents.json
├── docs/
│   └── workflow.md
├── .gitignore
└── README.md
```

## Tech & Skills

- n8n
- AI / LLM Integration
- Prompt Engineering
- Webhooks
- REST APIs
- JSON
- Customer Support Automation

## Security

No real API keys, access tokens, customer phone numbers, or private credentials are stored in this repository. Use n8n credentials or environment variables for production deployments.

## Production Improvements

For a production implementation, connect the workflow to an approved WhatsApp provider, add authentication and rate limiting, connect an AI provider, store conversation context securely, add logging, and implement a human handoff process.

## Author

Abdul Nafay — AI Engineer & Web Developer
