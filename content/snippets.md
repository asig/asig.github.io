---
title: Weekly Work Snippets
link: https://github.com/asig/snippets
---

A minimalist web app for documenting your daily work progress in a weekly dashboard. Entries are stored in PostgreSQL, and sign-in uses Google OAuth2.

The frontend is a React + TypeScript single-page app with multi-year week navigation, auto-saving cards and a rendered Markdown report view. The backend is a Go REST API. Deployment is via Docker Compose with a Caddy reverse proxy.
