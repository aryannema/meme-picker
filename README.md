# Meme Picker (Cat Meme Picker)

A small vanilla **HTML + CSS + JavaScript** project that lets you pick a **random cat meme** based on user-selected options (using data stored in `data.js`). The UI is built in `index.html`, styled with `index.css`, and the logic lives in `index.js`.

This project is mainly focused on practicing core JavaScript DOM + array methods.

---

## What I Learned / Practiced

This project was built to practice:

- `for...of` loops
- import/export style modular JS (using `data.js`)
- `.includes()`
- `event.target.id`
- DOM traversal with `parentElement`
- `classList.add()` / `classList.remove()`
- `querySelector()`
- working with **checkboxes**
- `filter()` for selecting matching memes ([GitHub][1])

---

## Project Structure

```
meme-picker/
│── index.html
│── index.css
│── index.js
│── data.js
└── images/
```

The repo contains these files/folder at the root level, including an `images/` folder for assets. ([GitHub][1])

---

## How It Works (High Level)

1. **Meme data** is stored in `data.js` (each meme item contains info used for filtering and displaying).
2. The page shows options (like “mood”/category checkboxes).
3. When the user selects options and triggers the action:
   - JavaScript filters the meme list using `filter()` + `.includes()`
   - picks one meme (randomly) from the filtered list
   - updates the DOM to display it

4. UI feedback is handled by adding/removing classes using `classList`.

---

## How To Run Locally

No setup needed.

1. Download/clone the repository
2. Open `index.html` in your browser

---
