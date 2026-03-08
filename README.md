# Daily Barriers Digest – M365 Copilot Agent

## Overview
The **Daily Barriers Digest** is a custom Microsoft 365 Copilot agent designed to summarize daily operational barriers and situations posted in a Slack channel. This agent converts raw, unstructured messages into a clean, categorized daily report that improves visibility, communication, and workflow efficiency.

This version uses **manual input**, allowing the user to paste Slack messages directly into the agent. It is designed to be upgraded later with Slack connectors or Power Automate integration depending on organizational permissions.

---

## Features
- Manual input workflow (paste Slack messages directly)
- Automatic categorization of barriers:
  - Staffing
  - Equipment
  - Safety
  - Systems
  - Quality
- Noise filtering and duplicate removal
- Condensed bullet‑point summaries
- Clean, easy‑to‑read daily report format
- Scalable design for future automation

---

## How It Works
1. User copies daily Slack messages from the operational channel.
2. User pastes the messages into the agent.
3. The agent:
   - Identifies barriers and operational issues
   - Groups similar items
   - Removes irrelevant chatter
   - Summarizes the content
4. The agent outputs a structured daily digest.

---

## Example Output
Daily Barriers & Situations – March 8, 2026

Equipment
- Conveyor jam at Dock 3 at 10:15 AM — resolved by maintenance

Staffing
- Ship Dock short-staffed from 5:00–7:00 PM

Systems
- FANS outage from 2:00–2:20 PM

Quality
- Three packages missing paperwork — escalated to PA

---

## Tech Stack
- Microsoft 365 Copilot
- Prompt Engineering
- Workflow Automation
- Slack (manual input workflow)
- Power Automate (future integration)
- GitHub (documentation and versioning)

## Agent Instructions
The following instruction set is used inside the Microsoft 365 Copilot agent to process daily Slack messages and generate a structured operational digest:

1. Read all pasted Slack messages provided by the user.
2. Identify barriers, issues, and operational situations mentioned in the messages.
3. Group similar items into the following categories:
   - Staffing
   - Equipment
   - Safety
   - Systems
   - Quality
4. Remove irrelevant chatter, greetings, or non-operational conversation.
5. Eliminate duplicate or repeated messages.
6. Condense long messages into clear, concise bullet points.
7. Highlight timestamps, locations, or key operational details when available.
8. Produce a clean, easy-to-read daily report using the following format:

Daily Barriers & Situations – <Date>

[Category]
- Summary item
- Summary item

[Category]
- Summary item

9. If no messages are provided, prompt the user to paste the daily Slack content.
10. Do not fabricate information; only summarize what the user provides.
