# Freedom — Awareness & Support Site (HTML/CSS)

A small multi-page static website that highlights regions facing hardship and gives
visitors a way to read about them and (eventually) send messages of support to
organizations working on the ground.

> **Status:** early prototype. The homepage, navigation, and one country page are in
> place; remaining country pages and the message-submission feature are in progress.

## 🎯 What It Does

- **Homepage** with a hover dropdown menu linking to individual region pages
  (Palestine, Sudan, Ukraine, Bolivia, Congo, Uyghurs, Rohingya).
- **Introductory message** explaining the goal: collect inspirational quotes/phrases
  to send to support organizations.
- **Per-region pages** (currently a styled heading; content to be added).


## 🛠️ Built With

- **HTML5** — semantic structure, multi-page navigation
- **CSS3** — flexbox navbar, hover-driven dropdown menu, custom backgrounds
- **Vanilla JavaScript** — inline `onclick` handlers for navigation *(planned refactor
  to real `<a href>` links)*

## 🚀 How to Run

No build step. Open `Home.html` in a browser, or serve the folder locally:

```bash
# from inside the Freedom/ folder
python3 -m http.server 8000
# then visit http://localhost:8000/Home.html
