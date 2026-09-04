# Zearup

Responsive front-end marketing site for Zearup Biomed, an early-stage biotechnology company researching microneedle interfaces for diabetes sensing and delivery. Built with React and Vite.

```bash
npm install
npm run dev
```

## Production

```bash
npm ci
npm run build
```

Production output is written to `dist/`. Static website imagery lives in `public/assets/` so Vercel can serve every `/assets/...` URL directly.

Vercel settings are pinned in `vercel.json`:

- Framework: Vite
- Build command: `npm run build`
- Output directory: `dist`
