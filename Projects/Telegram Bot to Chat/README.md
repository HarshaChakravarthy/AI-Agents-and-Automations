## Telegram Bot to Chat

### Problem statement:
Teams and communities want quick, reliable answers and small utilities without switching apps.

### Inputs:
Telegram messages/commands.

### Solution / Workflow:
Use a Telegram trigger to receive messages.
Route commands (/help, /id) vs free-text chat.
For chat, respond with a short LLM answer and links where appropriate.
Log minimal telemetry for troubleshooting.

### Tools & frameworks:
n8n • Telegram • OpenAI (LLM) • HTTP Request

### Recommendations:
Add an admin allow-list for sensitive commands.
Rate-limit per user to avoid abuse.
Keep answers brief; provide links for deeper reading.

### Conclusion:
A lightweight chat bot reduces friction and surfaces answers where the team already is.

### Note:
APIs & credentials not included: This repo contains only n8n workflows. No live API endpoints, keys, or third-party credentials are provided—configure your own in n8n (Settings → Credentials) before running.

### Workflow:
<img width="1918" height="913" alt="image" src="https://github.com/user-attachments/assets/2a79569b-f7ac-459d-98b7-2d9f14f70e4b" />
