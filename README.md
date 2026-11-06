# MarkFlow - Plain-Text Task Runner & Markdown Editor

> A local-first markdown task manager and automation runner designed with a retro-modern Notepad++ aesthetic[span_0](start_span)[span_0](end_span), built-in Gemini AI core integration, background scheduling, and seamless webhooks.

![MarkFlow Interface](https://img.shields.io/badge/Interface-Notepad++%20Style-darkgreen) ![Status](https://img.shields.io/badge/Status-Active%20Workspace-success) ![License](https://img.shields.io/badge/License-MIT-blue)

---

## 🚀 Why MarkFlow?

MarkFlow merges two major developer trends: **local-first plain-text notes** (the Obsidian/Notepad ecosystem) with **powerful local automation**. Developers and power users who love working with Markdown can now execute workflows directly from their notes without leaving the text editor.

### Key Highlights
* **Notepad++ Inspired UI**: Clean dark-mode IDE layout featuring file sidebars, tabs, line numbers, and a TUI output console[span_1](start_span)[span_1](end_span).
* **Task Runner Engine**: Parses standard Markdown checkboxes (`- [ ]`, `- [x]`) and executes custom directives (`@task`, `@ai`, `@webhook`, `@clean`, `@build`).
* **Gemini AI Core**: Optional AI integration allowing you to toggle the engine on/off, set custom system prompts, and inject runtime API keys to process smart notes.
* **Background Scheduler**: Configure automated background task runs on custom intervals or specific days/times of the week.
* **PDF User Manual Generator**: Built-in utility to download a detailed user manual directly as a PDF.
* **Cross-Platform Support**: Fully compatible with desktop modern browsers (supporting local folder access) and mobile/iOS sandboxed memory workspaces[span_2](start_span)[span_2](end_span).

---

## ⚙️ Markdown Task Directives Syntax

MarkFlow scans your `.md` files for checkbox items containing custom trigger tags:

```markdown
# Project Workflow Note

- [ ] Run standard local task @task Process current local logs
- [ ] Execute AI analysis on code architecture @ai Review security bottlenecks
- [ ] Dispatch event payload @webhook [https://api.yourdomain.com/hook](https://api.yourdomain.com/hook)
- [ ] Clean temporary files @clean --path ./build/tmp
- [ ] Trigger local build command @build npm run build
