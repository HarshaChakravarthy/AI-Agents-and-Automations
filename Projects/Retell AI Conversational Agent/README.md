## Retell AI Conversational Agent

### Problem statement:
Call centers and service lines face repetitive queries that can be resolved automatically with a natural voice interface.

### Inputs:
Caller audio/intent captured by Retell AI.

### Solution / Workflow:
Understand intent and entities (name, account, topic).
Use an agentic LLM to select tools: HTTP APIs, Sheets, search.
Execute actions and formulate a natural response.
Save call notes and optionally email a summary.

### Tools & frameworks:
n8n • Retell AI • OpenAI (LLM) • HTTP Request • Google Sheets

### Recommendations:
Add a fallback to a human when confidence is low.
Mask sensitive terms in stored transcripts.
Log tool inputs/outputs (without secrets) for quality review.

### Conclusion:
The voice agent handles common requests hands-free, improving responsiveness and freeing up staff time.

### Note:
APIs & credentials not included: This repo contains only n8n workflows. No live API endpoints, keys, or third-party credentials are provided—configure your own in n8n (Settings → Credentials) before running.

### Workflow:
<img width="1918" height="911" alt="image" src="https://github.com/user-attachments/assets/8f184661-dd44-44c4-8e88-0a0b4dcbc368" />
