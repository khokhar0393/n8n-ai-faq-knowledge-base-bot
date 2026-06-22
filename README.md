# AI FAQ Knowledge Base Bot

Author: Babar Abbas Khokhar

## Overview

An AI-powered FAQ and Knowledge Base chatbot built using n8n, OpenAI, Google Sheets, Gmail, and Webhooks.

The workflow automatically answers customer questions using a Google Sheets knowledge base. If the answer cannot be found, the request is escalated to the support team for manual review.

## Features

* AI-powered FAQ chatbot
* Google Sheets knowledge base
* Automated customer responses
* Human escalation for unknown queries
* Gmail integration
* OpenAI integration
* Structured output parsing
* Webhook support

## Workflow

Webhook → Google Sheets → Code Node → AI Agent → IF Condition

Known Question → Customer Auto Reply

Unknown Question → Support Team Escalation

## Knowledge Base Example

| Question            | Answer                                 |
| ------------------- | -------------------------------------- |
| SEO Pricing         | Our SEO services start from $500/month |
| Website Development | Website development starts from $1000  |
| Delivery Time       | Typical delivery time is 2–4 weeks     |
| Support             | We provide 24/7 support                |

## Technologies Used

* n8n
* OpenAI API
* Google Sheets
* Gmail
* Webhooks

## Use Cases

* Customer Support Automation
* FAQ Automation
* Help Desk Automation
* Knowledge Base Search
* Lead Support Systems

## Author

Babar Abbas Khokhar
AI Automation Developer
