# 🧩 Leads Tracker — Chrome Extension

This is the **Chrome Extension** version of the Leads Tracker project. It allows users to save URLs from their active browser tab or manual input and stores them locally using `localStorage`.

---

## 📌 Features

- Save the current browser tab URL
- Save manually entered URLs
- Persist data using `localStorage`
- Delete all saved leads with a double-click
- Clean, minimal popup UI

---

## 🚀 How to Install

1. Clone or download the repository.
2. Open Google Chrome and navigate to `chrome://extensions/`.
3. Enable **Developer mode** (toggle at the top right).
4. Click **Load unpacked**.
5. Select the `chrome_extension/` folder.
6. The extension will appear in your Chrome toolbar.

---

## 🗂️ File Overview
```
chrome_extension/
├── index.html # Extension popup layout
├── index.css # Styling for the popup UI
├── index.js # JavaScript logic (input, save, delete)
├── manifest.json # Chrome extension metadata and permissions
└── icon.png # Extension icon
```

---

## 🛠️ Technologies

- HTML5
- CSS3
- Vanilla JavaScript
- Chrome Extensions API
- LocalStorage

---

## 📎 License

This project is open-source and free to use for educational purposes.
