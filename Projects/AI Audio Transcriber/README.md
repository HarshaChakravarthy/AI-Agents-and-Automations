## AI Audio Transcriber

### Problem statement:
Teams struggle to capture accurate notes from calls and voice notes. Manual transcription and summarization are time-consuming.

### Inputs (Dataset):
Audio files or voice memos submitted via webhook or upload.
Optional speaker names/context.

### Solution / Workflow:
Validate format/size; reject unsafe types.
Transcribe using Whisper ASR (or equivalent).
Summarize with an LLM into action items, decisions, owners, and deadlines.
Deliver the transcript and summary via Gmail and log to Google Sheets.

### Tools & frameworks:
n8n • Whisper (ASR) • OpenAI (LLM) • Gmail • Google Sheets • Webhooks/HTTP

### Recommendations:
Chunk long audio to avoid timeouts.
Keep a consistent summary template to reduce back-and-forth.
Store minimal PII; avoid raw audio in long-term logs.

### Conclusion:
This workflow turns unstructured audio into usable insights, enabling faster follow-ups and better knowledge capture.

### Workflow:
<img width="1918" height="912" alt="image" src="https://github.com/user-attachments/assets/a015abef-ee95-4f94-a069-025467654de9" />
