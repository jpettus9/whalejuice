# WhaleJuice — Next.js Demo

(If any files are missing, use the previous ZIP: whalejuice-next.zip)


---
## Deploying to GitHub

### Via GitHub Web UI (no CLI)
1. Create a new repository on GitHub (no README).
2. Drag & drop **all files and folders** from this project into the repo page.
3. Commit. GitHub will render the README.

### Via command line
```bash
# inside the project folder
git init
git add .
git commit -m "Initial commit: WhaleJuice demo"
# replace with your repo
git branch -M main
git remote add origin https://github.com/YOUR_USER/whalejuice.git
git push -u origin main
```

### Run locally
```bash
npm install
npm run dev
# open http://localhost:3000 (/, /event)
```
