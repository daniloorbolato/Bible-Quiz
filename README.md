# Bible Quiz

Interactive Bible quiz app with multi-language support (English and Portuguese).

---

## What It Does

- Presents Bible questions with multiple choice answers
- Supports English and Portuguese
- Powered by Claude AI via a Cloudflare Worker backend
- Runs entirely in the browser — no build step, no framework

## Stack

- **HTML + CSS + JS** — single file app (`index.html`)
- **Cloudflare Worker** — API gateway to Claude
- **Claude AI** — generates and evaluates quiz questions

## How to Run

Open `index.html` in any browser. The app connects to the Cloudflare Worker backend automatically.
