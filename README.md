# Deepak AI Portfolio Website

A modern, single-page portfolio site focused on **Generative AI** and **Agentic AI** roles for Architect/Engineer job applications.

## Project Files

- `index.html` – Website structure and content
- `style.css` – Visual styling and responsive layout
- `script.js` – Small script for dynamic footer year

## Run Locally

Use Python's built-in static server:

```bash
python3 -m http.server 4173 --bind 0.0.0.0
```

Open:

- `http://localhost:4173`

---

## Deploy for Public Access

Below are two easy options. **GitHub Pages** is recommended.

## Option 1: GitHub Pages (Recommended)

### 1) Push this repo to GitHub

```bash
git remote add origin https://github.com/<your-github-username>/my-profile.git
git branch -M main
git push -u origin main
```

### 2) Enable GitHub Pages

1. Open your repository on GitHub.
2. Go to **Settings** → **Pages**.
3. Under **Build and deployment**:
   - Source: **Deploy from a branch**
   - Branch: **main**
   - Folder: **/(root)**
4. Click **Save**.

### 3) Public Link

Your site will be available at:

```text
https://<your-github-username>.github.io/my-profile/
```

> Example format only: `https://deepak-username.github.io/my-profile/`

---

## Option 2: Netlify Drop (Fastest no-code deploy)

1. Go to <https://app.netlify.com/drop>
2. Drag and drop this project folder (`my-profile`)
3. Netlify instantly provides a public URL like:
   - `https://your-site-name.netlify.app`

You can later connect your GitHub repo for automatic updates.

---

## Update Your LinkedIn / Content

Current LinkedIn profile in the site:

- <https://www.linkedin.com/in/work-with-deepak/>

If you want to update text/content, edit `index.html` and redeploy.

## Suggested Next Improvements

- Add your real profile photo
- Add concrete project case studies and metrics
- Add downloadable resume button
- Add custom domain (e.g., `deepakai.com`)
