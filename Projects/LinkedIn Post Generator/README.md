## LinkedIn Post Generator

### Problem statement:
Publishing quality, on-brand LinkedIn posts is slow. Teams want consistent tone and cadence.

### Inputs:
Short brief: topic, target audience, tone (concise/story/technical), CTA.

### Solution / Workflow:
Build prompts with tone and length controls.
Generate 2-3 post variants via LLM.
Optionally suggest an image idea or generate a prompt for a design tool.
Save drafts to Drive or send by email for approval.

### Tools & frameworks:
n8n • OpenAI (LLM) • Google Drive • Gmail • Prompt engineering

### Recommendations:
Maintain templates per persona (founder, product, hiring).
Set max length and brand rules (hashtags/emojis).
Add a simple toxicity/style check pass.

### Conclusion:
This workflow scales content creation without losing voice or quality.

### Note:
APIs & credentials not included: This repo contains only n8n workflows. No live API endpoints, keys, or third-party credentials are provided—configure your own in n8n (Settings → Credentials) before running.

### Workflow:
<img width="1918" height="911" alt="image" src="https://github.com/user-attachments/assets/e126f9f1-cb0f-4595-aded-6168f3b14ee7" />
