# n8n-form-to-gmail-ai-workflow
Automates form submissions by generating an AI response and sending it through Gmail using n8n.
<img width="2018" height="594" alt="image" src="https://github.com/user-attachments/assets/df9fe708-aed0-44c8-9fea-43334d7f437d" />

## Automated AI Form Responder
This project is an n8n workflow designed to automatically process form submissions, generate intelligent responses using an AI model, and deliver them via Gmail.

## Key Features
Form Trigger: Initiated by any external form submission (e.g., Google Forms, Typeform).
AI Content Generation: Uses an LLM (Message a model) to create context-aware, relevant text based on the submission data.
Time Control: A configurable Wait period allows for delayed, more human-like response timing.

Email Delivery: Sends the final AI-generated message to the required recipient using the Gmail node.

Requirements
n8n Instance (Self-hosted or Cloud).

Form Webhook or integration setup.

AI Service Credentials (e.g., Gemini, OpenAI) for the modeling node.

Gmail Service Account or connection.

Usage
Import the workflow into n8n.

Configure the On form submission node to receive data.

Customize the Message a model node's prompt to define the desired AI response style.

Set the recipient and subject fields in the Send a message node, dynamically inserting the form submitter's email.
