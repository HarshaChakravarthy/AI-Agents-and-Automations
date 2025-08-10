## Adding Title, Keywords for Stock Images — README.md

### Problem statement
Preparing images for stock platforms is slow and inconsistent. Creators spend time writing titles, descriptions, and keywords, which impacts discoverability and revenue.

### Inputs (Dataset)

Image files from Google Drive or URLs.
Optional existing metadata to refine.

### Solution / Workflow

Import images from Drive/URL.
Use a Generative AI LLM (GPT-4/3.5) to describe content and propose keywords.
Normalize wording (length, casing), deduplicate keywords, and apply SEO heuristics.
Write results to Google Sheets and return JSON for downstream tools.

### Tools & frameworks

n8n • OpenAI (LLM) • Google Drive • Google Sheets • Webhooks/HTTP • Prompt engineering

### Recommendations

Maintain prompt templates for style consistency and marketplaces’ rules.
Track rejected images/invalid URLs in a simple error log (DLQ).
Periodically review keywords against search trends.

### Conclusion
Automated metadata boosts listing throughput and consistency, improving search ranking and team productivity.

### Workflow
<img width="1918" height="907" alt="image" src="https://github.com/user-attachments/assets/067ac6b2-ffe5-4a59-8afd-a885ad973dea" />
