# 🚀 NKS Group Website — GitHub Pages Deployment Guide

## YOUR GITHUB ACCOUNT DETAILS
- **Username:** `sandilejoseph87`
- **Email:** `sandile.joseph@gmail.com`
- **Your website URL will be:** https://sandilejoseph87.github.io

---

## STEP 1: Log Into Your GitHub Account
1. Go to **https://github.com**
2. Click **"Sign in"** → enter `sandile.joseph@gmail.com` and your password ✅

---

## STEP 2: Create a New Repository
1. Click the **"+"** icon (top right) → **"New repository"**
2. Repository name: **`sandilejoseph87.github.io`** ⚠️ EXACT name required!
3. Set to **Public**
4. ✅ Check **"Add a README file"**
5. Click **"Create repository"**

---

## STEP 3: Upload Your Website Files
1. Click **"Add file"** → **"Upload files"**
2. Drag and drop ALL files from the website folder:
   - `index.html`, `about.html`, `services.html`, `industries.html`
   - `community.html`, `careers.html`, `contact.html`
   - The `css/` folder | The `js/` folder | The `images/` folder
3. Click **"Commit changes"** ✅

---

## STEP 4: Enable GitHub Pages
1. Click **"Settings"** tab → **"Pages"** (left sidebar)
2. Source: Branch **main** / Folder **/ (root)**
3. Click **"Save"**
4. Wait 2–5 minutes → your site is live at **https://sandilejoseph87.github.io** 🎉

---

## HOW TO ADD VACANCIES (Careers Page)
1. Go to repository → click `careers.html` → click ✏️ pencil icon
2. Find `<div class="vacancy-card">` and edit the job title, location, description
3. To add more: copy the entire `<div class="vacancy-card">...</div>` block, paste it, edit
4. Click **"Commit changes"** — live in 1–2 minutes!

## HOW TO ADD CSR PHOTOS (Community Page)
1. Upload photo to `images/community/` folder in GitHub
2. Edit `community.html` → find `<div class="gallery-placeholder">` 
3. Replace that div with: `<img src="images/community/your-photo.jpg" alt="Description"/>`
4. Commit ✅

## HOW TO ADD TEAM/FOUNDER PHOTOS (About Page)
1. Upload photos to `images/` folder — recommended names:
   - `khangela-kubheka.jpg` | `paul-silinda.jpg` | `dumisile-nene.jpg`
2. Edit `about.html` → find `<div class="team-photo-placeholder">` for each person
3. Replace with: `<img src="images/khangela-kubheka.jpg" alt="Khangela Kubheka"/>`
4. Commit ✅

---

## OPTIONAL: CUSTOM DOMAIN (www.nksgroup.co.za)
1. Settings → Pages → Custom domain → enter `www.nksgroup.co.za` → Save
2. Contact your domain registrar → add CNAME record:
   - Name: `www` | Value: `sandilejoseph87.github.io`
3. Wait up to 24 hours for DNS propagation

---
*NKS Group (Pty) Ltd — Precision. Reliability. Efficiency.*
