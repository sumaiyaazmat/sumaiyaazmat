<div align="center">

![Banner](Banner.png)

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=28&pause=1000&color=FF1E56&center=true&vCenter=true&width=500&lines=Hi%2C+I'm+Sumaiya+Azmat+%F0%9F%91%8B;Software+Engineer+in+Training;ML+%2B+Backend+Enthusiast;Nice+to+have+you+here!" alt="Typing SVG" />
</a>

### A passionate programmer from Pakistan 🇵🇰

<img src="https://komarev.com/ghpvc/?username=sumaiyaazmat&label=Profile%20Views&color=ff1e56&style=for-the-badge" alt="profile views" />

</div>

---

## 👩‍💻 About Me

- 🎓 BS Software Engineering student
- 🤖 Currently learning **Machine Learning** and **AI**
- 🚀 Building real-world ML projects with **FastAPI** and **MySQL**
- 💻 Passionate about Software Engineering and Backend Development
- 📚 Exploring Recommendation Systems, Data Science, and MLOps
- 🌱 Always learning something new
- ⚡ Fun fact: **It's not too late to shine.**

---

## 🚀 Currently Working On

**🛒 AI-Powered E-Commerce Recommendation System**
A full-stack e-commerce platform integrating Machine Learning, customer segmentation, personalized recommendations, FastAPI, and MySQL.

---

## 🛠️ Languages & Tools

<p align="left">
  <img src="https://skillicons.dev/icons?i=cpp,py,js,html,css,fastapi,mysql,git,github,vscode" alt="tech stack icons" />
</p>

---

## 📊 GitHub Stats

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=sumaiyaazmat&show_icons=true&theme=radical&hide_border=true&count_private=true" alt="GitHub stats" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=sumaiyaazmat&layout=compact&theme=radical&hide_border=true" alt="Top languages" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=sumaiyaazmat&theme=radical&hide_border=true&border_radius=8" alt="GitHub streak stats" />
</p>

## 📈 Contribution Graph

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=sumaiyaazmat&theme=react-dark&hide_border=true&area=true" alt="contribution activity graph" />
</p>

## 🐍 Contribution Snake

<p align="center">
  <img src="https://raw.githubusercontent.com/sumaiyaazmat/sumaiyaazmat/output/github-contribution-grid-snake-dark.svg" alt="contribution snake animation" />
</p>

> ℹ️ The snake animation above only appears once you add the GitHub Action workflow below to this repository (see **Setup** section).

---

## 🤝 Connect With Me

<p align="left">
  <a href="mailto:officialsumaiya15@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="email" />
  </a>
  <a href="https://linkedin.com/in/sumaiya-azmat-a04b27335" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="linkedin" />
  </a>
  <a href="https://instagram.com/sumaiyaazmat" target="_blank">
    <img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="instagram" />
  </a>
</p>

## ☕ Support Me

<a href="https://www.buymeacoffee.com/sumaiyaazmat" target="_blank">
  <img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="buy me a coffee" height="45" width="180" />
</a>

---

<details>
<summary>⚙️ Setup notes (click to expand)</summary>

**To make the contribution snake animation work:**

1. Create a repository named exactly `sumaiyaazmat` (must match your username) if you haven't already — this is your GitHub profile repo.
2. Add a workflow file at `.github/workflows/snake.yml` (included below).
3. Push it — the action runs on a schedule and on push, generating the SVG used above.

```yaml
name: generate contribution snake

on:
  schedule:
    - cron: "0 0 * * *"
  push:
    branches:
      - main
  workflow_dispatch: {}

permissions:
  contents: write

jobs:
  generate:
    runs-on: ubuntu-latest
    steps:
      - uses: Platane/snk/svg-only@v3
        with:
          github_user_name: ${{ github.repository_owner }}
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark

      - uses: crazy-max/ghaction-github-pages@v4
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
```

4. Double-check the badge usernames (`sumaiyaazmat`) throughout this file match your actual GitHub username — update them if not.

</details>
