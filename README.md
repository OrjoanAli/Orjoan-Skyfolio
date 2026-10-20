# ☁️ Skyfolio ✨

> A little sky where my work lives. Sunny by day, starry by night. 🌤️🌙

**🌐 Live site:** [orjoanali.github.io/Orjoan-Skyfolio](https://orjoanali.github.io/Orjoan-Skyfolio/)

---

## 🌈 What is this?

Hi, I'm **Orjoan Aldabaibah** 👋 a web developer and data analyst from Amman, Jordan.
Skyfolio is my personal portfolio, built **from scratch** with plain HTML, CSS and JavaScript.
No frameworks, no templates, no UI libraries. 🧡

## 🎀 Features

- ☀️🌙 **Day / Night theme**: one click turns the sunny sky into a starry night
  (the sun becomes the moon, the clouds drift away, and the stars come out and twinkle)
- 🌍 **English / Arabic switcher**: the whole page switches language and flips to right-to-left
- 📱 **Responsive**: Flexbox, Grid and media queries, so it looks good on phones too
- 🧭 **Sticky navbar**: jump to About, Skills, Projects, Education, Volunteering, Hobbies and Contact
- 🕰️ **Volunteering timeline**: my journey with the Linux Society, IEEE and more
- 💌 **Contact form**: with built-in validation

## 🧰 Built with

| | |
|---|---|
| 🧱 | HTML5 |
| 🎨 | CSS3: variables, Flexbox, Grid, animations |
| ⚡ | JavaScript (DOM, events, a translation dictionary) |
| 🌱 | Git and GitHub |

## 🔍 How it works

**Theme switcher** 🌗
Clicking the Theme button runs a function that flips the `data-theme` attribute on the `<html>` tag.
The CSS variables change with it, so the colors, sun, moon, clouds and stars all switch together.

**Language switcher** 🗣️
Every piece of text has a `data-translate` key. A JavaScript dictionary holds the English and
Arabic text, and clicking the language button swaps them and sets `lang` and `dir="rtl"` on the page.

## 🗂️ Project structure

```
├── index.html   the page structure
├── style.css    styles, day/night colors, sky animations
├── script.js    theme switcher and translation dictionary
└── images/      my photo
```

## 🚀 Run it locally

```bash
git clone https://github.com/OrjoanAli/Orjoan-Skyfolio.git
cd Orjoan-Skyfolio
xdg-open index.html   # Linux (use "open" on macOS, "start" on Windows)
```

## 🎓 Where this came from

Skyfolio started as my capstone project (Project 04) in the **Cyber and Web Essentials**
training at **42 Amman**. 🧑‍💻

## 📫 Let's connect

- 💼 [LinkedIn](https://www.linkedin.com/in/orjoan-aldabaibah-9984982b6)
- 🐙 [GitHub](https://github.com/OrjoanAli)
- ✉️ orjoanaldabaiba@gmail.com

---

<p align="center">Made with 💙 and a lot of ☕ by Orjoan</p>