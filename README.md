# 🖼️ The Great Image Heist — Profile Picture Cropper

> A delightful, interactive, chaos-infused profile picture cropper web application.

---

## 🚀 Quick Start (Local)

To run the project locally, open `index.html` directly in any web browser, or start a local server:

```bash
npx serve .
```

---

## 🐙 Push to GitHub / Git

Initialize and link to your GitHub repository:

1. **Create a new repository on GitHub**:
   - Go to [github.com/new](https://github.com/new)
   - Name it `the-great-image-heist` (or any name you prefer)
   - Do **not** initialize with README or .gitignore (we already created them)

2. **Link and push**:
   ```bash
   git remote add origin https://github.com/<YOUR-USERNAME>/<YOUR-REPO-NAME>.git
   git branch -M main
   git push -u origin main
   ```

---

## ▲ Host on Vercel

You can deploy this project to Vercel in two easy ways:

### Option A: Import via GitHub (Recommended)
1. Push your repository to GitHub (steps above).
2. Go to [vercel.com/new](https://vercel.com/new).
3. Connect your GitHub account and import your repository.
4. Click **Deploy**. Vercel will instantly build and host your app on a free `*.vercel.app` domain with automatic deployments on every `git push`.

### Option B: Deploy via Vercel CLI
Run the following in this folder:
```bash
npx vercel
```
- Follow the prompt to log in / connect your account.
- Accept default settings to deploy.
- For production deployment:
  ```bash
  npx vercel --prod
  ```
