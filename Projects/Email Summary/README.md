## Email Summary

### Problem statement
Long email threads create overload. Stakeholders need concise summaries to act quickly.

### Inputs (Dataset):
Recent Gmail threads or pasted email text.

### Solution / Workflow
Pull recent emails by time or label.
Group messages by conversation/topic.
Use an LLM to summarize with decisions, due dates, owners, and blockers.
Send a concise morning digest and optionally store highlights in Google Sheets.

### Tools & frameworks:
n8n • OpenAI (LLM) • Gmail • Google Sheets • Schedulers

### Recommendations:
Create tone presets (executive, support, engineering).
Guardrail prompts against hallucinating dates/owners.
Use filters to exclude newsletters/automated alerts.

### Conclusion:
Daily digests reduce context-switching, improve follow-through, and keep teams aligned.

### Note:
APIs & credentials not included: This repo contains only n8n workflows. No live API endpoints, keys, or third-party credentials are provided—configure your own in n8n (Settings → Credentials) before running.

### Workflow:
<img width="1918" height="907" alt="image" src="https://github.com/user-attachments/assets/85fd313a-8168-4a89-94fd-f8d537d674c2" />
