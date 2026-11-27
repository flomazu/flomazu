## Hi there 👋

I automate business processes: recurring manual work turned into tools that run
reliably, check their input and show what they did.

My current approach is dedicated building blocks that each do one job well and can
be combined into larger workflows, for example in a script or n8n. Where people
use them directly, they get a simple form or web front end on top.

**Current project**
- *[mail-merge](https://github.com/flomazu/mail-merge)*: personalised emails from an
  Excel or CSV list, with checks before sending, a report and no double sending.
  Tested in CI, optional Docker image.

  Next steps:
  - a web form for mail-merge (Flask)
  - mail merge as a native n8n workflow

- *Private Paperwork Parser (PPP)*: local-first document processing for personal paperwork.
  Turns photographed letters, scans and PDFs into a structured JSON (text, tables, positions, OCR confidence)
  as the local source of truth, plus pseudonymized Markdown that is safe to share with cloud tools.
