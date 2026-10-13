# Shivam's Developer Portfolio

A modern, fast, responsive developer portfolio featuring dark/light themes, dynamic particle canvas animations, and interactive project showcases. Built with pure HTML5, modern CSS, and vanilla JavaScript.

---

## 🚀 How to Deploy on Render

Render hosts static sites completely free with global CDN, automated SSL, and automatic deploys on git push.

### Step 1: Push your project to GitHub

If you haven't initialized Git yet, run these commands in this directory:

```bash
git init
git add .
git commit -m "Initial commit: Render deployment ready"
```

Then create a new repository on [GitHub](https://github.com/new) and push your code:

```bash
git branch -M main
git remote add origin https://github.com/<your-username>/<your-repo-name>.git
git push -u origin main
```

---

### Step 2: Deploy on Render

You can deploy using either of these two easy methods:

#### Method A: Using Render Blueprints (Recommended - 1 Click)

Because this repository includes a [`render.yaml`](render.yaml) file, Render can configure everything automatically:

1. Log in to [dashboard.render.com](https://dashboard.render.com/).
2. Click **New +** in the top right and select **Blueprint**.
3. Connect your GitHub repository.
4. Render will detect `render.yaml` and configure:
   - **Service Type**: Static Site
   - **Publish Directory**: `.` (Root)
   - **Build Command**: *(None needed)*
   - **Security Headers & Rewrite Rules**: Preconfigured
5. Click **Apply**. Your site will be live on a `*.onrender.com` URL within seconds!

#### Method B: Manual Static Site Setup

If you prefer setting it up manually without Blueprints:

1. Log in to [dashboard.render.com](https://dashboard.render.com/).
2. Click **New +** > **Static Site**.
3. Select your GitHub repository.
4. Fill in the deployment details:
   - **Name**: `shivam-portfolio` (or any name you choose)
   - **Branch**: `main`
   - **Build Command**: *(leave empty)*
   - **Publish Directory**: `.` (or `./`)
5. Click **Create Static Site**.

---

## 🛠 Local Development & Preview

You can preview the site locally in any of the following ways:

- **Directly in Browser**: Double-click [index.html](index.html) or [Shivam_Portfolio.html](Shivam_Portfolio.html).
- **Using Node / NPX**:
  ```bash
  npx serve .
  ```
  or:
  ```bash
  npm start
  ```
  and navigate to `http://localhost:3000`.

---

## 🌐 Custom Domain (Optional)

To connect your own domain (e.g. `yourname.dev`):
1. In the Render Dashboard, go to your Static Site settings.
2. Under **Custom Domains**, click **Add Custom Domain**.
3. Add your domain and update your DNS records (CNAME / ALIAS) as instructed by Render.
Render will automatically provision and renew a free Let's Encrypt SSL certificate for you.
