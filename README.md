# 🌿 Wildlife Ecology (2026) • 12-Week Interactive Quiz Portal

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live%20Ready-success?style=for-the-badge&logo=github)](https://pages.github.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-emerald?style=for-the-badge)](LICENSE)
[![Questions: 120](https://img.shields.io/badge/Questions-120%20Curated-blue?style=for-the-badge)](index.html)
[![PWA Ready](https://img.shields.io/badge/PWA-Installable-purple?style=for-the-badge)](site.webmanifest)

A modern, high-performance, and responsive interactive study and examination portal for the **Wildlife Ecology** course. Features **120 questions** covering all 12 weeks of the curriculum, with real-time analytics, instant answer feedback in Practice Mode, full Exam simulation with a question palette, and sleek dark/light theme support.

---

## 🌐 Live Demo & Deployment URL

Once deployed on GitHub Pages, your quiz portal will be live at:
```text
https://aditya-kumar-yadav.github.io/MOOC/
```

---

## 🚀 How to Deploy on GitHub in 3 Easy Steps

This repository is already 100% pre-configured for GitHub Pages. You can deploy it in less than 2 minutes.

### Step 1: Create a New Repository on GitHub
1. Log in to [GitHub](https://github.com/) and click **New Repository** (or visit [github.com/new](https://github.com/new)).
2. Name your repository (for example: `wildlife-ecology-quiz` or `wildlife-ecology`).
3. Leave it **Public** (required for free GitHub Pages).
4. **Do NOT** check "Add a README" or ".gitignore" (these are already included here).
5. Click **Create repository**.

### Step 2: Push this Repository to GitHub
Open your terminal / command prompt in this folder and run:

```bash
# 1. Add your GitHub repository as the origin remote (replace with your repo URL):
git remote add origin https://github.com/<YOUR-USERNAME>/<YOUR-REPOSITORY-NAME>.git

# 2. Ensure main branch is active:
git branch -M main

# 3. Push all files to GitHub:
git push -u origin main
```

*(If you haven't committed yet, run `git add .` and `git commit -m "Initial commit"` first).*

### Step 3: Enable GitHub Pages

You can choose either of two simple methods:

#### Option A: Zero-Config GitHub Actions (Recommended)
1. On your GitHub repository page, go to **Settings** > **Pages** (in the left sidebar).
2. Under **Build and deployment** > **Source**, select **GitHub Actions**.
3. That's it! The included [deploy.yml](.github/workflows/deploy.yml) workflow will automatically build and publish your site.

#### Option B: Deploy from Branch
1. On your GitHub repository page, go to **Settings** > **Pages**.
2. Under **Build and deployment** > **Source**, choose **Deploy from a branch**.
3. Under **Branch**, select `main` and folder `/(root)`.
4. Click **Save**.
5. Wait ~30–60 seconds, refresh the page, and GitHub will display your live URL!

---

## 📲 Sharing with Others

Once GitHub Pages is enabled:
- **Direct Link**: Share `https://<YOUR-USERNAME>.github.io/<YOUR-REPOSITORY-NAME>/` on WhatsApp, Telegram, Discord, or via email.
- **Social Previews**: Rich Open Graph cards and Twitter previews will show automatically when shared on social media.
- **Mobile PWA App**: Anyone opening the site on an iPhone or Android device can tap **"Add to Home Screen"** to install it like a native offline-ready app.

---

## ✨ Features & Highlights

- 📚 **12-Week Comprehensive Curriculum**: 120 meticulously curated questions spanning taxonomy, biodiversity, population dynamics, behavioral ecology, conservation, and ecosystem management.
- 🎯 **Dual Learning Modes**:
  - **Practice Mode**: Real-time answer validation, detailed rationales, and self-paced study.
  - **Exam Mode**: Timed exam simulation (120 minutes countdown), question status palette, no immediate reveals, and comprehensive post-submission report.
- 🎨 **Adaptive Themes**:
  - High-contrast Dark theme (default) designed for extended study sessions.
  - Crisp Light theme with smooth transitions.
  - Theme preference automatically saved in `localStorage`.
- 🧭 **Question Palette & Navigation**:
  - Jump to any question at any time.
  - Visual indicators for Answered, Unanswered, and Flagged items.
  - Full keyboard shortcuts support:
    - `1` – `4` or `A` – `D`: Select option
    - `Arrow Left` / `Arrow Right`: Navigate questions
    - `F`: Toggle question flag
- 📊 **Detailed Performance Analytics**:
  - Overall accuracy percentage, total time spent, and question-by-question review.
  - Week-by-week score breakdown to identify strengths and weaknesses.
- ⚡ **Zero External Backend / Dependencies**:
  - 100% client-side HTML5, CSS3, and modern Vanilla JavaScript.
  - Instant loading, zero database setup, zero server maintenance costs.

---

## 💻 Running Locally

You do not need any build tools or web servers. You can run the portal immediately:

### Simple Double-Click
Double-click `index.html` (or `wildlife_ecology_quiz.html`) to open it directly in any modern browser (Chrome, Edge, Firefox, Safari).

### Or Using a Local Web Server
If you prefer running via a local dev server:

```bash
# Python 3
python -m http.server 8000

# or Node.js npx
npx serve .
```
Then visit `http://localhost:8000` in your browser.

---

## 📁 Repository Structure

```text
├── .github/
│   └── workflows/
│       └── deploy.yml          # Automated GitHub Pages deployment workflow
├── .gitignore                  # Clean gitignore for OS and editor files
├── favicon.svg                 # Scalable vector favicon
├── index.html                  # Main web entry point (served by GitHub Pages)
├── LICENSE                     # MIT Open Source License
├── README.md                   # Project documentation and deployment guide
├── site.webmanifest            # PWA manifest for mobile home screen installation
└── wildlife_ecology_quiz.html  # Alternate standalone entry point
```

---

## 📄 License

This project is licensed under the [MIT License](LICENSE) - feel free to study, modify, and share!
