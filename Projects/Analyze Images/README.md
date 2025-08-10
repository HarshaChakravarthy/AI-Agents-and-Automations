## Analyze Images

### Problem statement:
Content teams need structured insight from images: labels, captions, and safety flags for moderation and search.

### Inputs:
Images from Drive/folders or URLs.

### Solution / Workflow:
Fetch images from the source folder/URL.
Perform image understanding with a Vision-enabled LLM.
Produce structured JSON: caption, labels, safety flags, confidence.
Persist to Google Sheets or a database and notify via email/chat if issues arise.

### Tools & frameworks:
n8n • Vision-enabled LLM • Google Drive • Google Sheets • HTTP APIs

### Recommendations:
Apply confidence thresholds and route low-confidence outputs for manual review.
Maintain a label taxonomy for consistency over time.

### Conclusion:
Consistent, machine-readable annotations reduce manual moderation and improve searchability across catalogs.

### Note:
APIs & credentials not included: This repo contains only n8n workflows. No live API endpoints, keys, or third-party credentials are provided—configure your own in n8n (Settings → Credentials) before running.

### Workflow:
<img width="1918" height="916" alt="image" src="https://github.com/user-attachments/assets/043904ea-a1ae-49ab-954c-443d87c5554a" />
