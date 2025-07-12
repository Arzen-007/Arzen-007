<!-- Banner Section -->
<p align="center">
  <img src="https://raw.githubusercontent.com/arzen-007/arzen-007/main/assets/banner.png" alt="Cyber Security Banner" />
</p>

<h1 align="center">Hi 👋, I'm Syed Muhammad Qammar Abbas Zaidi</h1>
<h3 align="center">A Passionate Cyber Security Enthusiast from Pakistan 🛡️</h3>

<!-- Typing Animation -->
<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=22&pause=1000&color=00ff00&center=true&vCenter=true&width=450&lines=Cybersecurity+Researcher+%F0%9F%94%91;Python+Automation+Lover+%F0%9F%92%BB;Linux+Fanatic+%F0%9F%90%9C;Open+Source+Contributor+%E2%9C%A8" alt="Typing SVG" />
</p>

---

### 🔐 About Me

- 🔭 I’m currently working on **RSA Cryptography**
- 🌱 Learning: **Python, C++, Bash**
- 🤝 Looking to collaborate on: **Key Logging Advancements**
- 💬 Ask me about **Cyber Security, Ethical Hacking, Linux & Scripting**
- 📫 Reach me at: **syedqammarzaidi2005@gmail.com**

---

### 🌐 Connect with Me:

<p align="left">
  <a href="https://www.linkedin.com/in/syed-muhammad-qammar-abbas-zaidi-b169b4369/" target="_blank">
    <img align="center" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linkedin/linkedin-original.svg" alt="LinkedIn" width="30" height="30" />
  </a>
  <!-- Twitter badge commented out -->
  <!-- <a href="https://twitter.com/" target="blank">
    <img align="center" src="https://img.shields.io/twitter/follow/?logo=twitter&style=for-the-badge" />
  </a> -->
</p>

---

### 🧰 Languages & Tools:

<p align="left">
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" width="40" height="40"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/c/c-original.svg" width="40" height="40"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/cplusplus/cplusplus-original.svg" width="40" height="40"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/bash/bash-original.svg" width="40" height="40"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg" width="40" height="40"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/flask/flask-original.svg" width="40" height="40"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original-wordmark.svg" width="40" height="40"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/git/git-original.svg" width="40" height="40"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original.svg" width="40" height="40"/>
</p>

---

### 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=arzen-007&show_icons=true&theme=tokyonight&hide_border=true" width="47%" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=arzen-007&layout=compact&theme=tokyonight&hide_border=true" width="47%" />
</p>

---

### 🔁 GitHub Activity Snake Animation

```yml
# .github/workflows/snake.yml

name: 🐍 Generate Snake Animation

on:
  schedule:
    - cron: "0 0 * * *" # Every day at midnight
  workflow_dispatch:

jobs:
  generate:
    runs-on: ubuntu-latest
    steps:
      - name: Generate Snake
        uses: Platane/snk@v3
        with:
          github_user_name: arzen-007
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark

      - name: Push to GitHub
        uses: crazy-max/ghaction-github-pages@v3
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
