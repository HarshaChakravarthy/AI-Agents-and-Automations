## AI Receptionist Conversational Flow (Bookings)

### Problem statement:
Booking, rescheduling, and canceling appointments over phone consumes staff time and creates bottlenecks.

### Inputs:
Caller name, phone, requested date/time, service/stylist preference.

### Solution / Workflow:
Capture details through a natural conversation.
Check calendar availability via API (e.g., Cal.com or your calendar).
Create/reschedule/cancel; send confirmation via email/SMS.
Log the interaction in Google Sheets/CRM.

### Tools & frameworks:
n8n • Retell AI • OpenAI (LLM) • Calendar API (Cal.com) • Google Sheets • Email/SMS

### Recommendations:
Offer alternative slots when conflicts arise.
Keep a clear policy around cancellations and reminders.
Provide an operator fallback for edge cases.

### Conclusion:
A 24/7 receptionist improves customer experience and ensures every inquiry is captured and confirmed.

### Note:
APIs & credentials not included: This repo contains only n8n workflows. No live API endpoints, keys, or third-party credentials are provided—configure your own in n8n (Settings → Credentials) before running.

### Workflow:
<img width="1918" height="913" alt="image" src="https://github.com/user-attachments/assets/86cdf457-3486-4b71-88bc-d98100820f85" />
