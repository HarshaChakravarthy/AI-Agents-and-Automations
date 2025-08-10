## Runway + ElevenLabs Video Generator

### Problem statement:
Producing short videos (promo/explainer) requires writing scripts, voiceover, and rendering—time-intensive for small teams.

### Inputs:
Script text + voice/style choices; optional asset links.

### Solution / Workflow:
Refine the script and shot list using an LLM.
Generate voiceover with ElevenLabs.
Render with Runway; poll job status until ready.
Save final video to Drive and log metadata in Sheets.

### Tools & frameworks:
n8n • OpenAI (LLM) • ElevenLabs (TTS) • Runway (video) • Google Drive • Google Sheets

### Recommendations:
Keep durations short for social channels.
Compress images/clips beforehand to reduce render time.
Handle quota/timeout errors with retries and clear alerts.

### Conclusion:
Teams can produce consistent video content quickly without manual stitching.

### Note:
APIs & credentials not included: This repo contains only n8n workflows. No live API endpoints, keys, or third-party credentials are provided—configure your own in n8n (Settings → Credentials) before running.

### Workflow:
<img width="1918" height="910" alt="image" src="https://github.com/user-attachments/assets/cba00485-0a67-4a22-ba4a-1260e3c50afb" />
