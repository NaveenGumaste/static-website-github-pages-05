# 🌐 Static Website Hosted with GitHub Pages

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Deployed-success?style=for-the-badge&logo=github)](https://pages.github.com/)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)

> **Elevate Labs DevOps Program — Task 6**  
> **Objective:** Deploy a simple, responsive HTML/CSS website for free using **GitHub Pages**.

---

## 🔗 Live Demo & Deliverables

- 🚀 **Live Website:** [https://NaveenGumaste.github.io/static-website-github-pages-05/](https://NaveenGumaste.github.io/static-website-github-pages-05/)
- 📁 **GitHub Repository:** [https://github.com/NaveenGumaste/static-website-github-pages-05](https://github.com/NaveenGumaste/static-website-github-pages-05)

_(Replace `<your-username>` and `<repo-name>` with your actual GitHub username and repository name once published.)_

---

## 📖 Project Overview

This project demonstrates the process of hosting and publishing static web content for free directly from a GitHub repository using **GitHub Pages**.

### Key Features

- **Modern & Responsive UI:** Clean design with custom CSS styling, flexible layout, and gradient styling.
- **Fast & Lightweight:** Built using pure HTML5 and embedded CSS without bulky frameworks or external dependencies.
- **Zero Cost & Automated Hosting:** Deployed seamlessly via GitHub's free static hosting infrastructure.

---

## 📂 Project Structure

```text
static-website-github-pages-05/
├── index.html       # Main HTML document with embedded CSS styling
└── README.md        # Project documentation and deployment guide
```

---

## 🛠️ Tech Stack

- **Markup:** HTML5
- **Styling:** CSS3
- **Version Control:** Git & GitHub
- **Deployment Platform:** GitHub Pages

---

## 🚀 Step-by-Step Deployment Guide

Follow these steps to deploy this website on GitHub Pages:

### 1. Initialize Git and Push Code to GitHub

Open your terminal in this directory and run:

```bash
# Initialize local git repository
git init

# Add all files to staging
git add .

# Commit changes
git commit -m "feat: initial commit of static website"

# Rename branch to main
git branch -M main

# Add your remote GitHub repository
git remote add origin https://github.com/<your-username>/<repo-name>.git

# Push changes to GitHub
git push -u origin main
```

### 2. Enable GitHub Pages

1. Navigate to your repository on [GitHub](https://github.com).
2. Click on **Settings** (top tab navigation).
3. In the left sidebar under the _Code and automation_ section, select **Pages**.
4. Under **Build and deployment** > **Source**, choose **Deploy from a branch**.
5. Under **Branch**:
   - Select `main` from the dropdown.
   - Leave the folder as `/ (root)`.
   - Click **Save**.

### 3. Access Your Live Site

- Wait 1–2 minutes for GitHub Pages to complete the deployment build.
- Refresh the **Pages** settings page until you see:
  > _"Your site is live at `https://<your-username>.github.io/<repo-name>/`"_
- Click the provided URL to view your live website!

---

## 💻 Local Development

To run or preview this project locally:

1. Clone this repository (or download the files):
   ```bash
   git clone https://github.com/<your-username>/<repo-name>.git
   cd <repo-name>
   ```
2. Open `index.html` directly in any web browser:
   - Double-click `index.html` in your file explorer, **or**
   - Use the VS Code extension **Live Server** (`Right Click -> Open with Live Server`).

---

## 🎯 Learning Outcomes

- Learned how to manage web assets and version control using Git and GitHub.
- Configured repository settings to enable automated deployment via GitHub Pages.
- Understood how static site hosting works in cloud-based modern DevOps workflows.

---

## 👤 Author

- **Name:** [Your Name]
- **GitHub:** [@your-username](https://github.com/<your-username>)
- **Program:** Elevate Labs DevOps
