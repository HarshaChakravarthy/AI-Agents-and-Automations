## YouTube Video Posting System

### Problem statement:
Uploading videos with correct titles, tags, descriptions, and thumbnails is repetitive and error-prone.

### Inputs:
Video file + raw metadata or a link to a queue.

### Solution / Workflow:
Validate asset and metadata.
Use an LLM to refine the title, tags, and short social copy.
Upload via YouTube API; set thumbnail and metadata.
Log to Google Sheets; send notifications with a preview link.

### Tools & frameworks:
n8n • OpenAI (LLM) • YouTube API (HTTP) • Google Sheets • Gmail/Telegram

### Recommendations:
Enforce length limits for titles/descriptions.
Schedule uploads for off-peak or target timezones.
Handle quota errors with exponential backoff.

### Conclusion:
Automated posting enforces standards, reduces mistakes, and speeds time-to-publish for content teams.

### Note:
APIs & credentials not included: This repo contains only n8n workflows. No live API endpoints, keys, or third-party credentials are provided—configure your own in n8n (Settings → Credentials) before running.

### Workflow:
<img width="1918" height="912" alt="image" src="https://github.com/user-attachments/assets/03ccdb86-4526-4146-a531-ed139a0d8a93" />
