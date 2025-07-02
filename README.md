# 🗂️ Leads Tracker Chrome Extension

A simple Chrome extension that allows you to save and track URLs from browser tabs and user inputs. Developed as part of a tutorial to learn **JavaScript** and **Chrome extension development**.

🔗 You can try out the extension by following the instructions below:

1. Clone the repository to your local storage.
2. Open Chrome and navigate to `chrome://extensions/`.
3. Enable **Developer mode** (toggle switch in the top right).
4. Click on **Load unpacked** and select the folder containing the extension files.
5. The extension should now be installed and visible in your Chrome toolbar.

---

## 📌 Description

This project is part of a tutorial to learn **JavaScript** and the basics of developing **Chrome extensions**. It demonstrates how to:

- Save the active tab’s URL to a list.
- Manually add URLs through an input field.
- Display the saved URLs dynamically in a list format.
- Clear all saved URLs with a double-click.

---

## 🔧 How It Works

- **SAVE TAB** button saves the URL of the active tab.
- **SAVE INPUT** button saves the URL entered by the user.
- **DELETE ALL** button clears all saved links when double-clicked.
- The saved URLs are stored in **localStorage** for persistence across sessions.
- The list of saved URLs is rendered dynamically in the extension popup.

---

## 🗂️ Folder Structure
```
leads_tracker_extension/
├── index.html # Contains the structure of the extension's popup
├── index.css # Styles the layout and buttons
├── index.js # Contains the JavaScript logic to handle the actions
└── manifest.json # Defines the metadata, permissions, and actions of the extension
```

---

## 🚀 Technologies Used

- HTML5
- CSS3
- Vanilla JavaScript (no frameworks)
- Chrome Extensions API

---

## 📎 License

This project is open-source and free to use for learning purposes.
