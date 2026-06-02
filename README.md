# Third-Year Medical School Grade Calculator by Yasser

An ultra-premium, cinematic, glassmorphism-styled SaaS dashboard designed specifically for third-year medical students to calculate their grades, monitor coefficient weights, and track academic status in real-time.

## Features
- **Cinematic UI/UX:** Built with luxury glassmorphism, ambient animated lighting, and deep navy/cyan color palettes.
- **Real-Time OS Engine:** Vanilla JavaScript calculations run instantly as you type without server latency.
- **Academic Accuracy:** Precisely mirrors the 26-coefficient structure containing "Unités" (Cardio, Neuro, etc.) and "Modules" (Immuno, Anapath, etc.).
- **Smart Status Indicator:** Dynamic color-coded academic status (Admis, Rattrapage, Ajourné).
- **Persistent Storage:** Saves data directly to the browser via `localStorage` allowing users to return without losing data.
- **100% Client-Side:** No frameworks, no external CSS libraries, entirely self-contained within one file.

## Deployment Guide

This project is fully static and production-ready. It requires **no build tools** (no Node.js, no Webpack).

### Option A: Vercel (Recommended)
1. Sign up/Login to [Vercel](https://vercel.com/).
2. Click **Add New** > **Project**.
3. Import your GitHub repository containing `index.html` and `vercel.json`.
4. Leave the Framework Preset to "Other" and click **Deploy**.
5. *Alternatively:* You can use Vercel CLI by typing `vercel` in your project folder.

### Option B: Netlify
1. Sign up/Login to [Netlify](https://netlify.com/).
2. Go to your team dashboard and click **Add new site** > **Deploy manually**.
3. Drag and drop the folder containing your `index.html` directly into the drop zone.
4. The site will be live instantly.

### Option C: GitHub Pages
1. Create a repository on GitHub and upload `index.html`.
2. Go to repository **Settings** > **Pages**.
3. Under "Source", select the `main` branch and root folder.
4. Click **Save**. Your site will be published at `https://[username].github.io/[repo-name]`.