![Workflow thumbnail](assets/thumbnail.svg)

![n8n](https://img.shields.io/badge/n8n-workflow-0EA5E9)
![license](https://img.shields.io/badge/license-MIT-green)
![status](https://img.shields.io/badge/status-ready-brightgreen)

# Detect multi-source transaction fraud and reconcile finances with OpenAI, Nvidia NIM, Gmail, Slack and Google Sheets

Advanced n8n automation for Detect multi-source transaction fraud and reconcile finances with OpenAI, Nvidia NIM, Gmail, Slack and Google Sheets.

## Overview
- Category: SecOps, AI Summarization
- Complexity: advanced
- Source: n8n workflow template export

## What This Automation Does
Automate real-time fraud detection across Stripe/PayPal/Plaid & banking APIs with AI risk scoring, instant Slack/Gmail alerts, and Sheets audit logs.

## Included Files
- `workflow.json`
- `metadata.json`

## Setup
1. Import `workflow.json` into n8n.
2. Configure required credentials for the services used in the workflow nodes.
3. Update any environment variables or static values inside nodes (API keys, URLs, IDs).
4. Run a test execution and then activate the workflow.

## Tech Stack

- `@n8n/n8n-nodes-langchain.agent`
- `@n8n/n8n-nodes-langchain.lmChatOpenAi`
- `@n8n/n8n-nodes-langchain.outputParserStructured`
- `n8n-nodes-base.aggregate`
- `n8n-nodes-base.code`
- `n8n-nodes-base.filter`
- `n8n-nodes-base.gmail`
- `n8n-nodes-base.httpRequest`
- `n8n-nodes-base.merge`
- `n8n-nodes-base.postgres`
- `n8n-nodes-base.scheduleTrigger`
- `n8n-nodes-base.set`
- `n8n-nodes-base.slack`
- `n8n-nodes-base.stickyNote`
- `n8n-nodes-base.switch`
- `n8n-nodes-base.webhook`

## Author

Murtaza Baig

## License
MIT License. See `LICENSE`.