# AI-Powered Support Ticket Automation

This project is a no-code automation that uses a multi-step workflow to categorize customer support tickets. The automation listens for new requests from a Google Form, uses an AI model to classify the request, and then routes it to the correct team via email.

## How It Works

1. A new request is submitted via Google Form.
2. A Make.com scenario is triggered.
3. The scenario uses the OpenRouter API and an AI model to categorize the request into "Sales Inquiry", "Technical Support", or "Billing Question".
4. The Google Sheet is updated with the AI's category.
5. A Router then sends an email notification to the correct department based on the category.
