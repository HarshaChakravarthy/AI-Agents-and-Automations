## Form Submission to Telegram

### Problem statement:
Leads and form submissions need instant, structured alerts—not messy inbox noise.

### Inputs:
Form payload via webhook (name, contact, interest, message).

### Solution / Workflow:
Validate required fields and sanitize inputs.
De-duplicate by hashing key fields (email+timestamp).
Send a formatted message to a Telegram channel or group.
Append to Google Sheets and optionally send a confirmation email.

### Tools & frameworks:
n8n • Telegram • Google Sheets • Gmail • Webhooks/HTTP

### Recommendations:
Add rate-limit protection and simple spam filters.
Use separate channels for high-priority vs general leads.

### Conclusion:
Teams get real-time, actionable alerts with clean data and a reliable audit trail.

### Note:
APIs & credentials not included: This repo contains only n8n workflows. No live API endpoints, keys, or third-party credentials are provided—configure your own in n8n (Settings → Credentials) before running.

### Workflow:
<img width="1918" height="913" alt="image" src="https://github.com/user-attachments/assets/63724bb0-70f6-4fec-a76c-82e7ab528683" />
