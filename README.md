<div align="center">
  <img alt="Counter-by-Count Logo" width="120" height="120" src="data:image/svg+xml;utf8,<?xml version='1.0' encoding='UTF-8'?>
  <svg xmlns='http://www.w3.org/2000/svg' width='240' height='240' viewBox='0 0 240 240'>
    <defs>
      <linearGradient id='g' x1='0' y1='0' x2='1' y2='1'>
        <stop offset='0%' stop-color='%236EE7F9'/>
        <stop offset='100%' stop-color='%23A78BFA'/>
      </linearGradient>
    </defs>
    <circle cx='120' cy='120' r='110' fill='url(%23g)'/>
    <circle cx='120' cy='120' r='100' fill='white' opacity='0.15'/>
    <g stroke='%23111827' stroke-width='16' stroke-linecap='round'>
      <line x1='70' y1='120' x2='170' y2='120'/>
      <line x1='120' y1='70'  x2='120' y2='170'/>
    </g>
  </svg>" />

  <h1 style="font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; font-weight: 800; letter-spacing: 0.5px; margin: 12px 0;">🔢 Counter‑by‑Count</h1>
  <p style="font-size: 14px; color: #555; margin-top: 0;">Simple, minimal counter app built with HTML, CSS, and JavaScript. Click to increment or decrement a number—perfect for learning DOM manipulation and basic event handling. ✨</p>
</div>

---

### 🌟 Features
- **Instant updates**: Counter value changes live on click
- **Keyboard‑free**: Simple button controls for increment/decrement
- **Clean UI**: Lightweight styling with a centered layout
- **Zero dependencies**: Pure HTML/CSS/JS

---

### 🚀 Demo
- Open the main HTML file in your browser to run locally. See Setup below.

---

### 📦 Project Structure

Current files in this folder:

```text
Counter-by-Count/
├─ html code          # HTML markup (references style.css and script.js)
├─ CSS code           # Styles for the page
├─ JS code            # Counter logic (increment/decrement)
└─ README.md
```

Recommended (rename to match references inside the HTML):

```text
Counter-by-Count/
├─ index.html    # was: "html code"
├─ style.css     # was: "CSS code"
├─ script.js     # was: "JS code"
└─ README.md
```

If you keep the current filenames, update the `<link>` and `<script>` paths inside the HTML accordingly. Otherwise, renaming to the recommended structure will make everything work out of the box.

---

### 🛠️ Setup & Usage
1. Option A (recommended): rename files as shown above.
2. Double‑click `index.html` (or the HTML file) to open in your browser.
3. Click "Increment" or "Decrement" to change the counter value.

> Note: The current HTML references `style.css` and `script.js`. Make sure your filenames match.

---

### 🧩 Tech Stack
- **HTML5**: structure
- **CSS3**: styling
- **JavaScript (ES5/ES6)**: behavior

---

### 🧪 How it works (quick peek)
- The counter value is stored in a JavaScript variable and rendered inside an element with `id="counterValue"`.
- Two functions, `increment()` and `decrement()`, update the value and re‑render it on button clicks.

---

### ✅ Roadmap / Ideas
- Add a reset button 🔁
- Persist value using `localStorage` 💾
- Add keyboard shortcuts ⌨️
- Add min/max and step control ⚙️

---

### 🤝 Contributing
Small project, but PRs and suggestions are welcome. If you change filenames, please also update the HTML references or adopt the recommended structure.

---

### 📄 License
No license specified yet. If you plan to share or reuse, consider adding an open‑source license (e.g., MIT).

---

### 📷 Screenshot (optional)
Add a screenshot or GIF here to showcase the UI.

---

### 🙌 Acknowledgements
Built as a simple practice project to demonstrate basic DOM events and UI updates.
