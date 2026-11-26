NOVA AI — Secure Backend Starter

Files:
- index.html: NOVA AI frontend
- api/chat.js: Vercel serverless endpoint; API key is server-only
- vercel.json: Vercel configuration

Deployment (phone-friendly outline):
1. Upload these files to a GitHub repository (index.html at repository root; api/chat.js inside api folder; vercel.json at root).
2. Import the repository into Vercel and deploy.
3. In Vercel Project Settings > Environment Variables add:
   Name: GEMINI_API_KEY
   Value: your Gemini API key
   Environment: Production (and Preview if you intend to test previews)
4. Redeploy after adding the variable.
5. Open the deployed site and test Chat.

Important:
- Do not paste the Gemini API key into the HTML, GitHub, or chat.
- This starter has no authentication or robust rate limiting; do not share it publicly yet.
- Protect your API key and monitor its usage in Google AI Studio.
