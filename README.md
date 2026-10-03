# AI-Powered Customer Trial Email Drafting Agent

An AI-powered workflow built using **n8n and OpenAI** to automate the drafting of professional customer trial follow-up emails.

The workflow uses an **AI Agent** to understand the provided customer and trial context, identify the appropriate scenario, and generate a clear and professionally formatted email. It supports multiple trial scenarios, including **active trials, inactive trials, approaching expiration, expired trials, and general follow-ups**.

Instead of automatically sending emails, the workflow creates a **Gmail draft**, allowing the user to review and validate the content before sending.

## Key Features

- AI-powered email drafting
- Scenario-based email generation
- Supports multiple customer trial stages
- Automatically generates the subject and email body
- Creates a formatted Gmail draft
- Human review before sending
- Professional and consistent communication
- Built with n8n and an OpenAI Chat Model

## Workflow

**Chat Trigger → AI Agent → OpenAI Chat Model → Gmail Draft**

The AI Agent also uses **Simple Memory** to retain relevant conversational context during the interaction.

## Supported Scenarios

- Active Trial
- Inactive / Not Activated Trial
- Approaching Expiration
- Expired Trial
- No Response / General Follow-Up

## Human-in-the-Loop

The workflow intentionally creates an email **draft rather than automatically sending it**. This ensures that AI-generated communication can be reviewed and edited by a human before it reaches the recipient.

## Tech Stack

- n8n
- OpenAI Chat Model
- AI Agent
- Gmail
- Simple Memory

<img width="1362" height="918" alt="Image" src="https://github.com/user-attachments/assets/b9cd6239-15db-4f92-833c-a395a46049d8" />
