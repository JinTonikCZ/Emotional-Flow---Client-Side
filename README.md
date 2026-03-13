# Emotional Flow

Emotional Flow is a student project for the *Client Side* course.
It is a fully client-side web app for tracking mood: the user logs emotions, intensity, and notes, and the app visualizes entries on a calendar and charts.

---

## 🚀 How to run

### 1) Open directly
1. Open `index.html` in a browser (double-click it or use `File → Open`).

> ⚠️ Some browsers may block scripts when opening files directly. If that happens, use the option below.

### 2) Run a local server (recommended)
1. Open a terminal in the project folder (`/workspaces/origin`).
2. Run:

```bash
python3 -m http.server 5000
```

3. Open in your browser:

```
http://localhost:5000
```

---

## 📦 What’s inside

- `index.html` — sign-in / sign-up page
- `analytics.html` — dashboard with calendar, charts, and check‑ins
- `script.js` — app logic (storage, visualization, event handling)
- `style.css` — styling and responsive layout
- `img/` and `attached_assets/` — images and assets

---

## 🧠 Skills you practice

- **HTML5**: semantic markup, forms, modals
- **CSS3**: Flexbox, Grid, responsive layout, theming, animations
- **JavaScript (ES6+)**:
  - DOM API (creating/removing elements, events)
  - Form handling and validation
  - `localStorage` for persistent storage
  - Data structuring (emotion entry format)
  - Date manipulation and time formatting
  - Building charts and heatmaps (canvas and/or DOM)
- **User Experience**:
  - Smooth step-based check-in flow
  - Mobile + desktop responsiveness
  - Friendly error messaging and validation
- **SPA-like architecture** (no frameworks)

---

## 📌 How to use

1. Register (email + password) or sign in
2. Do daily/periodic **check‑ins** (emotion → intensity → note)
3. View:
   - Calendar (emotion heatmap)
   - Weekly distribution chart
   - Day-by-day details

---

## 🧩 Possible improvements (future versions)

- Real backend storage (Node.js/Express, database)
- Charts using libraries (Chart.js, D3.js)
- Multi-user authentication and profiles
- Data export/import (CSV/JSON)
- Dark theme, localization, customizable emotions

---

> This project was created as a coursework assignment for the **Client Side** class.
