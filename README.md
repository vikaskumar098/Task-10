
# Alvy Page Clone 🔥✨

**A fully responsive landing page clone of the "Alvy" fashion/creative page — built with HTML + SCSS (compiled → CSS).**   
**GitHub Repo:** [📂 View Code](https://github.com/vikaskumar098/Task-10.git)

---

## 🚀 Overview
Alvy Page Clone is a modern, **mobile-first landing page** inspired by fashion and creative websites.  
It uses **semantic HTML** and **modular SCSS** with custom **mixins** for reusability and clean design.  
The layout includes a hero section, stats, team showcase, and a CTA block — all **fully responsive** and **JavaScript-free** ⚡.

---

## 🧩 Tech Stack
- 🧠 **HTML5** — semantic structure  
- 🎨 **SCSS (Sass)** — modular and maintainable styling  
- 🖼️ **Remixicon** — icon library via CDN  
- ☁️ **GitHub Pages** — free static hosting  

---

## ✨ Features
- ✅ Fully responsive for all screen sizes  
- ✅ Clean and reusable SCSS **mixins** (`@mixin flex-column()`, `@mixin card()`)  
- ✅ Elegant **hero section** with large background image  
- ✅ **Stats section** to display brand or product highlights  
- ✅ **Team cards** with hover effects & background images  
- ✅ **Contact CTA section** for user engagement  
- ✅ Lightweight — **No JavaScript**, only HTML + CSS  
- ✅ Easy to deploy on GitHub Pages  

---

## 📁 Project Structure

Below is the full structure of the project along with what each file does 👇  

```

Task-10/
├── index.html                # Main HTML file containing all sections of the website
├── style.scss                # Main SCSS file (source code for styles)
├── style.css                 # Compiled CSS output from SCSS (used for deployment)
├── style.css.map             # Source map file (for debugging SCSS)
├── card1.webp                # Team card image (used in the .card section)
├── card2.webp                # Team card image (used in the .card section)
├── card3.webp                # Team card image (used in the .card section)
├── view3 img.webp            # Section image (used in hero or stats section)
├── view4.webp                # Decorative/Background image
├── view7.webp                # Supporting section image
└── 63d2cb2934d35c4b4c5b51da_studio-hero-p-1600.webp  # Hero background image

````

### 📄 File Details:

- **`index.html`** →  
  Contains the structure of the website (hero, stats, team, contact).  
  Uses semantic tags like `<section>`, `<div>`, `<header>`, and `<footer>`.

- **`style.scss`** →  
  The main SCSS source file containing:
  - Custom mixins (`flex-column`, `card`)
  - Nested selectors for better organization
  - Modular styling for each section

- **`style.css`** →  
  The compiled version of SCSS — this file is linked in `index.html`.

- **Images (`.webp`)** →  
  Used as background and card images throughout different sections of the page.

---

## 🛠️ How to Run Locally

```bash
# 1️⃣ Clone the repository
git clone https://github.com/vikaskumar098/Task-10.git

# 2️⃣ Navigate into the folder
cd Task-10

# 3️⃣ Open the project
# Option 1: Open index.html directly in your browser
# Option 2: Use VS Code Live Server extension
# Option 3: Run local server with Python
python -m http.server 5500
# Then visit → http://localhost:5500
````

---

## 🎨 Working with SCSS

If you edit the `style.scss` file, you’ll need to **recompile** it into CSS.

### Using Sass globally:

```bash
npm install -g sass
sass --watch style.scss:style.css
```

### Using local setup (optional):

```bash
npm init -y
npm install --save-dev sass
# Add in package.json scripts:
# "watch:sass": "sass --watch style.scss:style.css"
npm run watch:sass

## 📌 Notes

* 🪶 Keep image names consistent with HTML references.
* 🧩 Use `alt` attributes for accessibility.
* 🧠 All SCSS mixins are reusable — great for scaling multiple projects.
* 📱 Always test on mobile and desktop before deployment.

---

## 🤝 Contributing

1. Fork this repository
2. Create a new branch (`feature/new-section`)
3. Commit changes and push
4. Create a Pull Request 🎉

---

## 📝 License

This project is licensed under the **MIT License** — feel free to use or modify it!

---

## 👨‍💻 Author

**Vikas Kumar**
*🌐 [LinkedIn](https://www.linkedin.com/in/vikas0905)
*💻 [GitHub](https://github.com/vikaskumar098)

---

⭐ **If you liked this project, don’t forget to give it a star on GitHub!** ⭐
