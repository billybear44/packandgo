# ✈️ Pack & Go — Installation Guide

## What you're getting
A fully installable app that lives on your iPhone/iPad Home Screen,
works 100% offline, and opens full-screen like a native app.
No App Store. No Mac. No cost.

---

## Step 1 — Get a free GitHub account (2 min)

1. On your iPad/iPhone, open Safari and go to: **https://github.com**
2. Tap **Sign up** and create a free account
3. Verify your email

---

## Step 2 — Create a new repository (1 min)

1. Once logged in, tap the **+** icon (top right) → **New repository**
2. Repository name: `packandgo` (lowercase, no spaces)
3. Make sure it's set to **Public**
4. Tick **"Add a README file"**
5. Tap **Create repository**

---

## Step 3 — Upload the app files (3 min)

You need to upload these files/folders from the zip:
```
index.html
manifest.json
sw.js
icons/  (the whole folder with all icon-*.png files)
```

**On iPad using GitHub's web interface:**

1. Open your new repository on GitHub
2. Tap **Add file** → **Upload files**
3. Upload `index.html`, `manifest.json`, `sw.js`
4. Tap **Commit changes**

**For the icons folder:**
1. Tap **Add file** → **Create new file**
2. In the filename box type: `icons/placeholder.txt`
3. Add any text content, commit it
4. Now go back, tap **Add file** → **Upload files**
5. Upload all the `icon-*.png` files — they will land in the `icons/` folder

---

## Step 4 — Enable GitHub Pages (1 min)

1. In your repository, tap the **Settings** tab (⚙️)
2. Scroll down to **Pages** in the left sidebar
3. Under **Source**, select **Deploy from a branch**
4. Branch: **main** | Folder: **/ (root)**
5. Tap **Save**
6. Wait ~60 seconds, then your app is live at:
   **https://YOUR-USERNAME.github.io/packandgo/**

---

## Step 5 — Install to Home Screen (30 seconds)

1. Open Safari on your iPad or iPhone
2. Go to: `https://YOUR-USERNAME.github.io/packandgo/`
3. Wait for it to fully load
4. Tap the **Share button** (the box with an arrow pointing up ↑)
5. Scroll down and tap **"Add to Home Screen"**
6. Tap **Add**

**That's it!** Pack & Go now appears on your Home Screen with its
own icon, opens full-screen with no browser address bar, and works
completely offline — just like a native app.

---

## Your app URL
Once deployed, bookmark this:
`https://YOUR-USERNAME.github.io/packandgo/`

Share it with family so they can install it on their devices too!

---

## Troubleshooting

**"Add to Home Screen" not appearing?**
→ Make sure you're using Safari (not Chrome or Firefox)
→ The option only appears in Safari on iOS/iPadOS

**App not working offline?**
→ Open the app in Safari once while connected to Wi-Fi
→ The service worker will cache everything automatically
→ After that first load, it works with no internet

**Icons look wrong on Home Screen?**
→ Delete the app from Home Screen, go back to the URL in Safari, and re-add it

---

*Built with ❤️ as a Progressive Web App (PWA)*
