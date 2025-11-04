# 🌐 My DevOps GitHub Pages

Welcome to my automated GitHub Pages site!  
This project demonstrates continuous integration and content automation using **GitHub Actions**.  
Every few hours, this page automatically updates with my latest GitHub activities 🚀

---

## 🧩 About This Project

This project was created as part of the **DevOps Assignment: Publish with GitHub Pages + Auto Activity Log**.

### 🧠 Objectives
- Automate README updates using GitHub Actions.
- Display real-time GitHub activity logs.
- Sync README content to GitHub Pages automatically.
- Demonstrate CI/CD workflow integration.

---

## ✨ My GitHub Activity Log

Here’s a list of my latest GitHub activities automatically updated every few hours 🚀

<!--RECENT_ACTIVITY:start-->
<!--RECENT_ACTIVITY:end-->

📅 **Last updated:** _(auto-updated by GitHub Actions)_

---

## ⚙️ Workflow Overview

The automation process uses a custom workflow file  
located at **`.github/workflows/activity-log.yml`**, which performs:

1. **Fetch recent activity** using `Readme-Workflows/recent-activity@main`
2. **Update timestamp** to show the latest update time
3. **Commit and push** changes to `README.md`
4. **Sync** automatically to GitHub Pages via `index.md`

---

## 🪄 Technology Stack

| Category | Tool / Service | Description |
|-----------|----------------|-------------|
| CI/CD | **GitHub Actions** | Automates build, test, and deploy pipelines |
| Hosting | **GitHub Pages** | Hosts static content directly from the repo |
| Data Source | **GitHub API** | Provides recent activity data |
| Formatter | **Markdown + Liquid (Jekyll)** | Generates the web layout dynamically |

---

## 💡 How It Works

```mermaid
flowchart TD
    A[Schedule or Manual Trigger] --> B[GitHub Action Runs]
    B --> C[Fetch Recent Activity]
    C --> D[Update README.md]
    D --> E[Commit & Push Changes]
    E --> F[GitHub Pages Deploys Updated Site]
