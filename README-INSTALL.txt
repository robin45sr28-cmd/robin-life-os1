ROBIN LIFE OS V12.0 — TRANSLATE & EXPLAIN

Files:
- index.html: website app
- manifest.webmanifest and icons: installable web app metadata
- ai-backend/: server-side AI API (keeps API key out of browser)
- render.yaml: Render Blueprint configuration
- INSTANT-AI-QUESTIONS-BN.txt: Bengali instant questions and backend setup guide

Release notes:
- Instant question chips now submit immediately with one tap.
- Example questions cover AI explanation, Python, Java, maths, general knowledge, study planning, translation and web coding.
- Existing Life OS sections and local data functionality are retained.

IMPORTANT: The ZIP cannot itself publish your site or turn on hosted AI. Deploy the backend and configure OPENAI_API_KEY in your hosting provider's secret environment settings, then save the backend URL in AI Assistant and use Test connection. Never put API keys in index.html or a public GitHub repository.

For full setup, read INSTANT-AI-QUESTIONS-BN.txt and ai-backend/README.md.

V12.0 additions:
- One-tap English translation, Bangla translation, explain in Bangla, explain in English, and grammar correction.
- Paste or type text in the AI Assistant box, then tap the relevant action.
- These actions require the AI backend for full generative answers.
