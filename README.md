# 🌐 My DevOps GitHub Pages

Welcome to my automated GitHub Pages site!  
This project demonstrates continuous integration and content automation using **GitHub Actions**.  
Every few hours, this page automatically updates with my latest GitHub activities 🚀

---

## 🧩 About This Project

This project was created as part of the **DevOps Assignment: Publish with GitHub Pages + Auto Activity Log**.

### 🎯 Objectives
- Automate README updates using GitHub Actions.
- Display real-time GitHub activity logs.
- Generate automatic changelog based on commits.
- Sync README content to GitHub Pages automatically.
- Demonstrate CI/CD workflow integration.

---

## ✨ My GitHub Activity Log

Here’s a list of my latest GitHub activities automatically updated every few hours 🚀  

<!--RECENT_ACTIVITY:start-->
<!--RECENT_ACTIVITY:end-->

---

## 🧾 Recent Commits

Below are the 5 most recent commits automatically pulled from this repository 🔄  

<!--COMMITS:start-->
<!--COMMITS:end-->

---

## ⚙️ Workflow Overview

The automation process uses a custom workflow file  
located at **`.github/workflows/activity-log.yml`**, which performs:

1. **Fetch recent activity** using `Readme-Workflows/recent-activity@main`
2. **Generate recent commit changelog** from `git log`
3. **Update timestamps** to show the latest update/deployment time
4. **Commit and push** changes to `README.md`
5. **Sync** automatically to GitHub Pages via `index.md`

---

## 🧠 How It Works

```mermaid
flowchart TD
    A[Schedule or Manual Trigger] --> B[GitHub Action Runs]
    B --> C[Fetch Recent Activity]
    C --> D[Generate Commit Log]
    D --> E[Update README Timestamps]
    E --> F[Commit & Push Changes]
    F --> G[GitHub Pages Deploys Updated Site]
