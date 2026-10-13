# Shivam Yadav — Developer Portfolio

A fast, responsive, and cinematic developer portfolio featuring dark & light modes, dynamic canvas animations, and interactive project showcases. Built with pure HTML5, modern CSS, and vanilla JavaScript for maximum performance and zero build dependencies.

---

## ✨ Features

- **🌓 Theme Switching**: Seamless dark and light modes with system preference detection and `localStorage` persistence.
- **🎨 Interactive Canvas & Particles**: Dual-layer animated color mesh and interactive particle network responding to pointer moves.
- **📱 Fluid & Full-Width Layout**: Modern edge-to-edge layout that scales smoothly across mobile, tablet, and ultra-wide displays.
- **💼 Interactive Project Showcase**: Tilt and spotlight-enabled 3D cards displaying full-stack projects and tech chips.
- **🛠 Comprehensive Tech Stack**: Highlights proficiency in C++, Python, JavaScript, React, Node.js, FastAPI, Flask, SQL, Docker, and CS fundamentals.
- **📋 One-Click Email Copy**: Quick-copy email address (`shivamyadav952004@gmail.com`) with animated confetti burst.
- **🚀 100% Render Ready**: Preconfigured with `render.yaml` for instant 1-click deployment on Render Static Sites.

---

## 📁 Project Structure

```
Portfolio/
├── index.html        # Main entry point (HTML5, styling & scripts)
├── render.yaml       # Render Blueprint configuration for deployment
├── package.json      # Scripts for local development server
├── .gitignore        # Git ignore rules
└── README.md         # Documentation & deployment guide
```

---

## 🚀 Deployment on Render

This portfolio is configured for zero-configuration hosting on **Render Static Sites** (Free global CDN, automated SSL, and automatic deploys on every `git push`).

### Method 1: Using Render Blueprint (Recommended — 1 Click)

1. Log in to [Render Dashboard](https://dashboard.render.com/).
2. Click **New +** in the top right corner and choose **Blueprint**.
3. Select your repository: **`shivam123yadav/portfolio`**.
4. Render will read [`render.yaml`](render.yaml) automatically and set up:
   - **Service Type**: Static Site
   - **Publish Directory**: `.` (Root)
   - **Build Command**: *(None required)*
   - **Security Headers & Rewrites**: Enabled
5. Click **Apply**. Your portfolio will be live in seconds!

### Method 2: Manual Static Site Setup

1. In the [Render Dashboard](https://dashboard.render.com/), click **New +** → **Static Site**.
2. Connect your GitHub repository: **`shivam123yadav/portfolio`**.
3. Configure the fields:
   - **Name**: `shivam-portfolio` (or your choice)
   - **Branch**: `main`
   - **Build Command**: *(leave empty)*
   - **Publish Directory**: `.`
4. Click **Create Static Site**.

---

## 🛠 Local Development & Preview

You can run and test the website locally in any of the following ways:

### 1. Direct Browser Opening
Double-click [`index.html`](index.html) or open it with your browser.

### 2. Using VS Code Live Server
Right-click [`index.html`](index.html) in VS Code and select **Open with Live Server**.

### 3. Using Node / NPM
```bash
# Using npx (no install needed)
npx serve .

# Or using npm
npm start
```
Then navigate to `http://localhost:3000` in your browser.

---

## 🌐 Custom Domain Setup (Optional)

To link your own custom domain (e.g. `shivamyadav.dev`):
1. In your Render Dashboard, navigate to your Static Site settings.
2. Under **Custom Domains**, click **Add Custom Domain**.
3. Enter your domain name and follow Render's instructions to add CNAME/ALIAS records to your DNS provider.
Render automatically generates and renews a free Let's Encrypt SSL certificate.

---

## 📬 Contact

- **Name**: Shivam Yadav
- **Degree**: B.Tech in Computer Science (2024 – 2028)
- **Email**: [shivamyadav952004@gmail.com](mailto:shivamyadav952004@gmail.com)
- **GitHub**: [github.com/shivam123yadav](https://github.com/shivam123yadav)
- **LinkedIn**: [linkedin.com/in/](https://linkedin.com/)

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).
