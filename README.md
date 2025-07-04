# ArgoCD Presentation

Done with https://github.com/webpro/reveal-md

🚀 1. Install reveal-md
```bash
npm install -g reveal-md
```

📋 2. Create your Markdown slides
Create a file slides.md

🧠 3. Preview your slides locally
```bash
reveal-md slides.md --theme black
```

🌐 4. Host on GitHub Pages
  - Create a GitHub repo (e.g. argocd-slides).
  - Add slides.md and in package.json, add:
```json
"scripts": {
  "start": "reveal-md slides.md --static docs",
  "deploy": "gh-pages -d docs"
}
```
  - Install dependencies:
```bash
npm install reveal-md gh-pages
```
  - Generate static site:
```bash
npm run start
npm run deploy
```
  - Enable GitHub Pages from the docs/ folder.
Now your slides are available at https://roman-muller.github.io/argocd-presentation/.