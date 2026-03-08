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
