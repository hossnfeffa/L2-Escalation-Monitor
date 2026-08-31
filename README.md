# ⚡ L2 Escalation Monitor

An AI-powered Power Automate workflow that monitors Tier-2 escalation ticket discussions, compiles message thread activity, analyzes ownership and escalation status using AI Builder / Azure OpenAI, and triggers automated triage actions based on classification outcomes.

---

## 📌 Project Overview

Managing L2 ticket discussions across Teams and support channels often leads to dropped updates, unclear ownership, and delayed resolution times. 

This workflow automates the tracking process by:
1. **Monitoring Discussions:** Listening for updates, responses, and activity on active L2 escalation threads.
2. **Parsing Telemetry:** Aggregating full message histories and meta-data from ticket discussions.
3. **AI Status Analysis:** Utilizing AI models to evaluate whether a ticket is actively being worked, awaiting client feedback, requiring tier-3 escalation, or stalled.
4. **Automated Triage:** Triggering conditional notifications, updating ticket statuses, or routing to the appropriate team lead based on the AI output.

---

## 📁 Repository Structure

```text
L2-Escalation-Monitor/
├── docs/                                    # Workflow diagrams & process flowcharts
│   └── FlowChart.pdf
├── prompts/                                 # AI Builder / Azure OpenAI prompt templates
│   └── Analyze Ticket Ownership AI Prompt
├── solutions/                               # Power Automate solution export package (.zip)
│   └── L2EscalationMonitor_20260831195903.zip
└── README.md                                # Project documentation
