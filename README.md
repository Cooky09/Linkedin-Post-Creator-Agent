# Linkedin-Post-Creator-Agent
Multi-agent AI content automation workflow demonstrating agent orchestration, prompt engineering, automated quality checks, and email delivery.
# LinkedIn Content Creator AI Agent

A multi-agent AI workflow built with n8n that automatically generates, reviews, and delivers LinkedIn content based on professional expertise, technical knowledge, and ongoing learning.

## Overview

Creating consistent LinkedIn content can be time-consuming. This workflow automates the entire process, from topic selection to final quality review.

The system uses three specialised AI agents that collaborate to produce authentic, technically credible LinkedIn posts aligned with a long-term professional narrative.

Every week, the workflow:

1. Reviews a curated knowledge base containing skills, experience, interests, and previous content.
2. Selects the most relevant topic and angle.
3. Generates a LinkedIn post.
4. Critiques and improves the post.
5. Emails the final version for review and publishing.

## Architecture

```text
Knowledge Base
      │
      ▼
Content Strategist Agent
      │
      ▼
LinkedIn Writer Agent
      │
      ▼
Quality Critic Agent
      │
      ▼
Email Delivery
```
## Workflow Overview

[![Workflow Overview](verview.png](screenshots/screenshotsworkflow-overview.png)

## Multi-Agent Architecture

[![Architecture](verview.png](screenshots/screenshotsmulti-agent-architecture.png)

## Sample Output

[![Sample Overview](verview.png](screenshots/screenshotgenerated-post.png)
## AI Agents

### Content Strategist Agent

Responsible for:

- Analysing experience, skills, and learning goals
- Selecting high-value content topics
- Avoiding repetitive content
- Maintaining a long-term professional narrative
- Creating content strategies for downstream agents

### LinkedIn Writer Agent

Responsible for:

- Transforming strategy into a LinkedIn post
- Maintaining a natural engineering voice
- Ensuring technical credibility
- Producing engaging, publication-ready content

### Quality Critic Agent

Responsible for:

- Authenticity checks
- Technical accuracy reviews
- Removing unsupported claims
- Improving clarity and readability
- Producing the final approved version

## Features

✅ Multi-Agent Architecture

✅ Automated Topic Selection

✅ AI-Powered Content Generation

✅ Content Quality Assurance

✅ Knowledge-Driven Personalisation

✅ Weekly Content Automation

✅ Email Delivery

✅ Low-Maintenance Workflow

## Tech Stack

- n8n
- Ollama
- Llama 3.1
- Gmail
- Google Docs
- Prompt Engineering
- Multi-Agent Systems

## Workflow Process

1. Retrieve content history and knowledge base information.
2. Generate a content strategy using the Content Strategist Agent.
3. Create the LinkedIn post using the Writer Agent.
4. Validate and improve the content using the Quality Critic Agent.
5. Deliver the final post via email.
6. Store content history for future topic selection.

## Example Use Cases

- Personal branding
- Learning in public
- AI and software engineering content
- Technical thought leadership
- Consistent LinkedIn publishing

## Future Improvements

- Direct LinkedIn publishing
- Retrieval-Augmented Generation (RAG)
- Analytics-driven topic selection
- Multi-platform content generation
- Content performance tracking

## Skills Demonstrated

- AI Agents
- Agent Orchestration
- Workflow Automation
- Prompt Engineering
- AI Content Generation
- LLM Applications
- n8n Development
- AI Evaluation
- Software Engineering

---

This project demonstrates how specialised AI agents can collaborate to automate a real-world content creation workflow while maintaining authenticity, quality, and consistency.
