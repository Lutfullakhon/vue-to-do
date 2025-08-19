# Vue TODO – Per-Tab Projects

A single-page TODO app built with **Vue 3 (CDN)** that treats **each browser tab** as a separate project.
Project title is editable (updates the page title), tasks support **subtasks (infinite depth)**, **search**, and **JSON import/export**. All data persists via `localStorage`.
<img src="https://socialify.git.ci/Lutfullakhon/vue-to-do/image?language=1&owner=1&name=1&stargazers=1&theme=Light" alt="vue-to-do" width="640" height="320" />

## Features

- **Per-tab project**: each tab is an independent project (no in-tab project switcher).
- **Editable project title** (syncs to `document.title`).
- **Tasks**
  - Add / delete
  - Mark done / undone
  - **Subtasks with unlimited depth**
- **Search** across task titles/descriptions (persists across reloads).
- **Import / Export** project as JSON.
- **Auto-save** to `localStorage` (survives reloads).
- **No build tools**; runs by opening `index.html`.

## Live Demo

- GitHub Pages: _add your link here after enabling Pages_
- Repository: _add your repo link here_

## Getting Started

### Option A — Quick run
Just open `index.html` in your browser (double-click).

### Option B — Local server (recommended)
Use VS Code + “Live Server” extension or any static server:
```bash
npx serve .
# or
python -m http.server 5173
