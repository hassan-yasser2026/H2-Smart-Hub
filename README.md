<div align="center">
<img width="1200" height="475" alt="GHBanner" src="https://ai.google.dev/static/site-assets/images/share-ais-513315318.png" />
</div>

# Run and deploy your AI Studio app

This contains everything you need to run your app locally.

View your app in AI Studio: https://ai.studio/apps/776352a4-6d27-43d0-aaf9-e9e22e029b4e

## Run Locally

**Prerequisites:**  Node.js

1. Install dependencies:
   `npm install`
2. Set the `GEMINI_API_KEY` in [.env.local](.env.local) to your Gemini API key
3. Run the app in development mode:
   `npm run dev`
4. For a production-like serving test, run:
   `npm run build`
   `npm run start`

The server now serves the React app correctly in both dev and production modes and keeps the API endpoints available under `/api/*` and `/v1beta/*`.
