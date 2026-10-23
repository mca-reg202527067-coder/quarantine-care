# QuarantineCare — Front-end prototype

## Run locally
1. Install Node.js (LTS).
2. Extract this folder.
3. In the project folder run:
   ```bash
   npm install
   npm run dev
   ```
4. Open the local URL shown by Vite.

## Deploy to Vercel
1. Create a GitHub repository and upload the contents of this folder (package.json, index.html, src/).
2. Sign in to Vercel and choose **Add New → Project**.
3. Import the GitHub repository.
4. Framework preset: **Vite**. Build command: `npm run build`. Output directory: `dist`.
5. Click **Deploy**. Copy the generated `https://...vercel.app` URL and submit that live URL in the assessment's Google Drive submission option.

## Demo
- Use the role switcher in the top-right to explore Administrator, Nurse and Doctor workflows.
- Patient data persists in this browser via localStorage.
- Use Reset site data in your browser's site settings to restore the original sample dataset.
- All data is fictional. This is a UI/workflow prototype, not a clinical system. It has no backend, secure authentication, or multi-user sync.
