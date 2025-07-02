# 🗂️ Leads Tracker

**Leads Tracker** is a learning project designed to help users save and manage URLs from their browser or manual inputs. This project is split into two implementations:

- 📦 [Chrome Extension](./chrome_extension/README.md): Save URLs from browser tabs using `localStorage`.
- 📱 [Mobile Web App](./mobile_app/README.md): Save user-input URLs using **Firebase Realtime Database** with a responsive, PWA-friendly UI.

---

## 📁 Folder Structure
```
leads_tracker/
├── chrome_extension/ # Chrome extension implementation
│ ├── index.html
│ ├── index.css
│ ├── index.js
│ ├── manifest.json
│ └── icon.png
│
├── mobile_app/ # Mobile web app implementation
│ ├── assets/ # PWA icons and favicon
│ ├── index.html
│ ├── index.css
│ ├── index.js
│ └── site.webmanifest
│
└── README.md # General overview (this file)
```
---

## 📌 Overview

This project demonstrates:

- URL input through input box and event listeners
- Dynamic rendering using the DOM
- Persistent data handling
  - `localStorage` (Chrome Extension)
  - `Firebase` (Mobile App)
- Clean, minimal user interfaces
- Chrome Extension and PWA fundamentals

---

## 🚀 Technologies Used

- HTML5 & CSS3
- Vanilla JavaScript
- Chrome Extensions API
- Firebase Realtime Database
- PWA (Progressive Web App) features

---

## 📎 License

This project is open-source and intended for educational purposes.
