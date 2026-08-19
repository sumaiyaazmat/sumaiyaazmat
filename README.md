<div align="center">

![Banner](Banner.png)

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=26&pause=1000&color=FF1E56&center=true&vCenter=true&width=550&lines=Hi%2C+I'm+Sumaiya+Azmat+%F0%9F%91%8B;BS+Software+Engineering+Student;Learning+Machine+Learning+%26+AI;Building+with+FastAPI+%2B+MySQL;Nice+to+have+you+here!" alt="Typing SVG" />
</a>

<p>
  <img src="https://komarev.com/ghpvc/?username=sumaiyaazmat&label=Profile%20Views&color=ff1e56&style=for-the-badge" alt="profile views" />
  <img src="https://img.shields.io/github/followers/sumaiyaazmat?label=Followers&style=for-the-badge&color=ff1e56" alt="followers" />
</p>

</div>

<br>

## 👩‍💻 About Me

```yaml
name: Sumaiya Azmat
location: Pakistan 🇵🇰
role: BS Software Engineering Student
currently_learning: [Machine Learning, Artificial Intelligence]
building_with: [FastAPI, MySQL, Python]
interests: [Recommendation Systems, Data Science, MLOps, Backend Development]
fun_fact: "It's not too late to shine."
```

<br>

## 🚀 Currently Building

<table>
<tr>
<td width="70">🛒</td>
<td>

**AI-Powered E-Commerce Recommendation System**
A full-stack e-commerce platform integrating Machine Learning, customer segmentation, and personalized product recommendations — powered by FastAPI on the backend and MySQL for data storage.

</td>
</tr>
</table>

<br>

## 🛠️ Languages & Tools

<p align="left">
  <img src="https://skillicons.dev/icons?i=cpp,py,js,html,css,fastapi,mysql,git,github,vscode" alt="tech stack icons" />
</p>

<br>

## 📊 GitHub Stats

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=sumaiyaazmat&show_icons=true&theme=radical&hide_border=true&count_private=true" alt="GitHub stats" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=sumaiyaazmat&layout=compact&theme=radical&hide_border=true" alt="Top languages" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=sumaiyaazmat&theme=radical&hide_border=true&border_radius=8" alt="GitHub streak stats" />
</p>

<br>

## 📈 Contribution Graph

<p align="center">
  <img src="https://ghchart.rshah.org/ff1e56/sumaiyaazmat" alt="GitHub contribution chart" />
</p>

<details>
<summary>⚠️ Graph not loading? Click here</summary>
<br>

This usually means one of two things:

1. **Private contributions are hidden** — go to `github.com/settings/profile` → *"Contributions & activity"* → enable **"Include private contributions on my profile."** Public tools can't count private-repo commits otherwise.
2. **The service is briefly rate-limited** — refresh after a minute, or swap the image URL above for one of these alternates:
   - `https://github-contributions-api.jogruber.de/v4/sumaiyaazmat?type=svg`
   - `https://activity-graph.herokuapp.com/graph?username=sumaiyaazmat&theme=react-dark`

</details>

<br>

## 🐍 Contribution Snake

<p align="center">
  <img src="https://raw.githubusercontent.com/sumaiyaazmat/sumaiyaazmat/output/github-contribution-grid-snake-dark.svg" alt="contribution snake animation" />
</p>

> Needs a one-time GitHub Action setup — see **Setup Notes** at the bottom of this file.

<br>

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

<br><br>

---

<details>
<summary>⚙️ Setup Notes (click to expand)</summary>
<br>

**To activate the contribution snake animation:**

1. Make sure you have a repository named exactly `sumaiyaazmat` (matching your username) — this is your special GitHub profile repo.
2. Add the file below at `.github/workflows/snake.yml` in that repo.
3. Push to `main` — the action generates the SVG on a schedule and on every push.

yaml
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

       uses: crazy-max/ghaction-github-pages@v4
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}


**If the contribution graph shows "Can't fetch any contribution":**

- Enable private contributions in your GitHub profile settings (see above), or
- Swap in one of the fallback graph URLs listed in the "Graph not loading?" section above.

**General:** double-check every `sumaiyaazmat` reference in this file matches your actual GitHub username exactly (case-sensitive).

</details>
