# Frieren: Beyond Journey's End - Landing Page

> This is a fan-made landing page project for the anime 'Frieren: Beyond Journey's End' (葬送のフリーレン), built to practice and showcase advanced front-end animations and layout techniques.

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://en.wikipedia.org/wiki/HTML5)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://en.wikipedia.org/wiki/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://en.wikipedia.org/wiki/JavaScript)
[![GSAP](https://img.shields.io/badge/GSAP-88CE02?style=for-the-badge&logo=greensock&logoColor=white)](https://greensock.com/gsap/)

---

## 🚀 Live Demo

**[>> Clique aqui para ver o site ao vivo <<](https://seu-usuario.github.io/seu-repositorio/)**

*(Instrução: Substitua o link acima pelo link do seu site no GitHub Pages, Vercel, etc.)*

---

## 📸 Previews

| Home Section | Characters Section | About Me Section |
| :---: | :---: | :---: |
| ![Home Section Preview](previews/home.jpg) | ![Characters Section Preview](previews/characters.jpg) | ![About Me Section Preview](previews/about-me.jpg) |

*(Instrução: Crie uma pasta chamada `previews` no seu projeto, adicione suas 3 imagens (`home.jpg`, `characters.jpg`, `about-me.jpg`) e o GitHub irá mostrá-las aqui.)*

---

## 📝 About The Project

I created this landing page project for "Frieren" using only **HTML, CSS, and vanilla JavaScript**, with **GSAP (GreenSock Animation Platform)** to handle the complex animations.

The entire design was made by me in **Figma**. The project also features two beautiful fanarts I found on Google Images, used in the Hero and "About Me" sections.

**⚠️ Responsiveness Note:**
Please be aware that this project is **not yet fully responsive**. It was designed and optimized for a **1920x1080 (16:9)** monitor. While it has a basic media query for mobile, there may be layout flaws on other resolutions like 1600x900. I plan to address these responsiveness issues in the future.

---

## ✨ Features

* **Custom Loading Screen:** An initial loading animation before the main content appears.
* **Animated Sections:** Each section has its own choreographed entrance animation.
    * The "Home" section animates on page load.
    * The "Characters" section animates on scroll, triggered by **ScrollTrigger**.
* **Interactive Character Switcher:** A fully functional and animated character selector that dynamically changes the section's content and background.
* **Infinite Diagonal Slider:** A custom-built, infinitely looping slider for the "About Me" section, created with CSS animations and `clip-path`.
* **Smooth Scrolling Navigation:** A header that smoothly navigates between page sections.

---

## 🛠️ Technologies Used

* **HTML5**
* **CSS3**
    * Flexbox for layout
    * `position: absolute` for complex layering
    * `@keyframes` for the infinite slider
    * `clip-path` for custom shapes
* **Vanilla JavaScript** for interactivity
* **GSAP (GreenSock Animation Platform)**
    * `Timeline` for choreographing complex animation sequences.
    * `ScrollTrigger` plugin to trigger animations on scroll.

---

## ⚙️ How to Run Locally

To run this project on your local machine, simply follow these steps:

1.  Clone the repository:
    ```sh
    git clone [https://github.com/seu-usuario/seu-repositorio.git](https://github.com/seu-usuario/seu-repositorio.git)
    ```
2.  Navigate to the project folder:
    ```sh
    cd seu-repositorio
    ```
3.  Open the `index.html` file in your favorite browser.

---

## 🎨 Design & Credits

* All UI/UX design was created by me from scratch in **Figma**.
* The character fanarts used in the project were sourced from public searches on Google Images. All rights and credits go to their respective original artists.
