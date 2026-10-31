ROBIN LIFE OS — BACKEND SETUP

The website files and backend service are included in this ZIP. The backend code is ready, but it is NOT online until you deploy it and add your own API key in the hosting dashboard.

QUICK SETUP:
1. Upload/commit the ZIP contents to the root of your GitHub Pages repository. Do not remove ai-backend/ or render.yaml.
2. In Render, create a Blueprint using that same GitHub repository.
3. In Render service Environment, add OPENAI_API_KEY using a key you create on the official OpenAI API platform. Never put the key in GitHub or send it in chat.
4. Deploy and open your service's /health URL; check that configured is true.
5. On the website open AI Assistant, enter only the backend service root URL (e.g. https://your-service.onrender.com), then save.

Full steps and troubleshooting are in ai-backend/README.md.
