<!-- 🔥 Stylish & Animated GitHub Profile README for Vansh Dhalor -->

<!-- ===== Animated Typing Intro ===== -->
<h1 align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=26&pause=1000&color=C5AA6A&center=true&vCenter=true&width=600&lines=Hi+👋,+I'm+Vansh+Dhalor;Frontend+Developer+%7C+Web+Developer;Crafting+Modern+%26+Responsive+UI" alt="Typing SVG" />
</h1>

---

<!-- ===== About Me ===== -->
<p align="center">
  <img src="https://img.shields.io/badge/Frontend-Developer-%23c5aa6a?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Web-Developer-%234c3c3c?style=for-the-badge" />
</p>

<p align="center">
  🚀 <b>Results-driven Frontend & Web Developer</b> with expertise in <b>React, Tailwind, Firebase</b>.<br/>
  🎨 Passionate about building <b>modern, responsive, and stylish UIs</b> with animations & smooth UX.<br/>
  📚 Always learning & experimenting with new frontend technologies.
</p>

---

## 🎨 Tech Stack
<p align="center">
  <a href="#"><img src="https://skillicons.dev/icons?i=html,css,js,react,tailwind,firebase,git,github,netlify,vercel,mysql" alt="Tech Stack"/></a>
</p>

---

## 🎓 Education
📖 **Bachelor of Computer Applications (BCA)**  
🎯 Chandigarh University (2022 – 2025)  

---

## 🚀 Featured Projects
<p align="center">
  <a href="https://vansh-dhalor.netlify.app">
    <img src="https://img.shields.io/badge/🌐%20Portfolio-Visit%20Now-%23c5aa6a?style=for-the-badge" />
  </a>
</p>

- 🛍️ **Fashionbycara** → Responsive E-commerce UI with React + Tailwind  
- 🎶 **Music Lover App** → Spotify-inspired music player UI  
- 📈 **Stocks & Trading Site** → Stock tracking UI with live charts  

---

## 📊 GitHub Stats
<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=vansh-frontend&show_icons=true&theme=tokyonight&hide_border=true" height="180em"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=vansh-frontend&layout=compact&theme=tokyonight&hide_border=true" height="180em"/>
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=vansh-frontend&theme=tokyonight&hide_border=true" height="180em"/>
</p>

---

## 🐍 Contribution Animation
> ⚡ To enable this, you must add a GitHub Action in your repo called `generate-snake.yml`.

```yaml
# .github/workflows/generate-snake.yml
name: Generate Snake Animation

on:
  schedule: 
    - cron: "0 */12 * * *"
  workflow_dispatch:

jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - uses: Platane/snk@v3
        with:
          github_user_name: vansh-frontend
          outputs: dist/github-contribution-grid-snake.svg
      - name: Push to GitHub
        uses: EndBug/add-and-commit@v9
        with:
          message: "Generated snake animation"
          add: "dist/github-contribution-grid-snake.svg"
