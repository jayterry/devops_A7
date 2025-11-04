🌐 My DevOps GitHub Pages

Welcome to my automated GitHub Pages site!
This project showcases continuous integration (CI) and content automation using GitHub Actions.

Every few hours, this page automatically updates with my latest GitHub activities 🚀

🧩 About This Project

This project was created as part of the DevOps Assignment: Publish with GitHub Pages + Auto Activity Log, demonstrating the use of automation pipelines to keep content fresh and synchronized.

🎯 Objectives

Automate README updates using GitHub Actions

Display real-time GitHub activity logs

Generate an automatic changelog from commits

Sync README content to GitHub Pages automatically

Demonstrate CI/CD workflow integration

✨ My GitHub Activity Log

Here’s a list of my latest GitHub activities, updated automatically every few hours 🚀

<!--RECENT_ACTIVITY:start--> <!--RECENT_ACTIVITY:end-->
🧾 Recent Commits

Below are the five most recent commits automatically pulled from this repository 🔄

<!--COMMITS:start--> <!--COMMITS:end-->
⚙️ Workflow Overview

The automation process is managed by
.github/workflows/activity-log.yml, which performs the following tasks:

Fetches recent activity using Readme-Workflows/activity-config@main

Generates a recent commit changelog from git log

Updates timestamps to reflect the latest update and deployment

Commits and pushes the changes to README.md

Syncs the README content automatically to GitHub Pages via index.md

🕒 Deployment Status

📅 Last updated: YYYY-MM-DD HH:MM:SS (UTC+8)
🚀 Last deployed: YYYY-MM-DD HH:MM:SS (UTC+8)
