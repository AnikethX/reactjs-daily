# 📅 Day 1 – React.js Learning Summary

## 1️⃣ Understanding `npm` & `npx`
- **npm**: Node Package Manager – installs packages permanently (can be global or local).
- **npx**: Executes packages temporarily without installing globally.
- **Basic Commands**:
```bash
npm install -g create-react-app    # Install CRA globally
npx create-react-app app-name      # Create a new React app
npm start                          # Start development server
```

---

## 2️⃣ Project Folder Structure
When you create a React app using `create-react-app`, you get:
```
node_modules/       # Installed dependencies
public/             
  index.html        # Main HTML file
src/
  App.js            # Main component
  index.js          # Entry point, renders App.js into index.html
.gitignore          # Files/folders to ignore in Git
package.json        # Project metadata & dependencies
package-lock.json   # Dependency version lock
README.md           # Project info
```

---

## 3️⃣ Important Files
- **`public/index.html`**
  - Contains `<div id="root"></div>` → React components render here.
  - `<noscript>` → Warns user if JavaScript is disabled.
- **`src/index.js`**
  - Entry point of React app.
  - Imports `App.js` and renders it into `root` div in `index.html`.
- **`src/App.js`**
  - Main UI component.
  - Contains JSX (JavaScript + HTML).
  - Can be styled using CSS.

---

## 4️⃣ Key Notes
- React uses a **component-based architecture**.
- JSX allows you to write HTML-like syntax inside JavaScript.
- `npm start` launches development server on `localhost:3000`.
- `package.json` tracks dependencies; `package-lock.json` ensures consistent installs.
- `"use strict";` enables strict JavaScript mode for cleaner code.

---

## 5️⃣ Practice Covered
- Installing Node.js & npm.
- Creating first React project.
- Exploring folder structure.
- Understanding how `index.js` and `App.js` work together.
- Learning role of `public/index.html` and `root` div.

---

✅ **End of Day 1** – Learned how to set up React, run it locally, and understand the basic project structure.
