# Tania Medellín Ortiz — Portfolio

A single-page portfolio in berry, pink and chalk. Plain HTML, CSS and JS in one file: no build step, no dependencies.

## Files
- `index.html` — the whole site (colours live in `:root` at the top of the `<style>` block)
- `src/page.html` — the same page without the document wrapper (used for the Claude preview)

## Edit in Antigravity
1. Open this folder in Antigravity (File → Open Folder).
2. Preview: open `index.html` in a browser, or run `npx serve .` in the terminal.

## Push to GitHub
```bash
git init
git add .
git commit -m "Initial portfolio"
git branch -M main
git remote add origin https://github.com/<your-username>/tania-portfolio.git
git push -u origin main
```

## Deploy on Vercel
1. vercel.com → Add New → Project → import the `tania-portfolio` repo.
2. Framework preset: **Other**. Leave build command and output directory empty.
3. Deploy. Every push to `main` redeploys automatically.
4. Optional: add a custom domain under Project → Settings → Domains.
