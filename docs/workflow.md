# Workflow Documentation

## Flow

1. **WhatsApp Webhook** receives an incoming message from the configured provider.
2. **Prepare Message** extracts the sender and message text.
3. **Build AI Prompt** creates structured instructions for the support agent.
4. **AI Processing Input** prepares the request for the selected AI provider.
5. Connect the AI output to a response node and a human-escalation branch for production use.

## Production Extension

Add authentication, rate limiting, conversation memory, AI provider credentials, response sending, logging, and a human handoff path before deploying.

## Security

Never commit real API keys, access tokens, customer phone numbers, or other secrets. Store credentials in n8n credentials or environment variables.
