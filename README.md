# ShidduchLink (Bulletproof Starter)

This starter is designed to deploy on Vercel without the common mistakes:
- Uses Next.js App Router (`/app`).
- Background image is **exactly** `public/bg.jpg` and referenced as `/bg.jpg`.
- No `app/public` folder.
- Fonts have explicit weights to avoid build failures.

## Run locally
1. Install Node.js (LTS)
2. In the folder:
   - `npm install`
   - `npm run dev`

## Deploy (GitHub → Vercel)
1. Create a new GitHub repo
2. Upload ALL files and folders from this zip to the repo root
3. In Vercel: New Project → Import the repo → Deploy
4. Test background image: visit `https://YOUR_DOMAIN/bg.jpg`
