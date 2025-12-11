<h1 align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=32&duration=3000&pause=800&color=00E8FF&center=true&vCenter=true&width=800&lines=I'm+Jegan+S;Full-Stack+Developer+in+Progress;CSBS+Student+%7C+Tech+Explorer;Always+Learning+%26+Growing" />
</h1>

<p align="center">
  <img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%" />
</p>


<p align="center">
  🎓 Third-Year <b>Computer Science and Business Systems</b> Student <br>
  💻 Passionate about building efficient, scalable, and user-focused software solutions. <br>
  🚀 Aiming to blend <b>technology</b>.
</p>

---

## 🌱 Currently Learning

* Full-Stack Web Development
* Data Structures & Algorithms
* Backend Development with Python
* Database Management Systems
* Cloud Basics

---

## 🧠 About Me

* 🔥 Highly motivated & always improving
* 📘 Learning advanced JavaScript & modern frontend practices
* ⚡ Love building projects that solve real-world problems
* 🧩 Strong problem-solving mindset
* 🎯 Consistency is my superpower

---

## 💻 Tech Stack

### 🚀 Languages

![Java](https://img.shields.io/badge/Java-%23ED8B00.svg?style=for-the-badge\&logo=java\&logoColor=white)
![Python](https://img.shields.io/badge/Python-%233776AB.svg?style=for-the-badge\&logo=python\&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-%23F7DF1E.svg?style=for-the-badge\&logo=javascript\&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-%23E34F26.svg?style=for-the-badge\&logo=html5\&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-%231572B6.svg?style=for-the-badge\&logo=css3\&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-%2300758F.svg?style=for-the-badge\&logo=database\&logoColor=white)

### 🗃️ Databases

![MySQL](https://img.shields.io/badge/MySQL-%234479A1.svg?style=for-the-badge\&logo=mysql\&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-%23003B57.svg?style=for-the-badge\&logo=sqlite\&logoColor=white)

### 🧰 Tools & Technologies

![Git](https://img.shields.io/badge/Git-%23F05033.svg?style=for-the-badge\&logo=git\&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-%23007ACC.svg?style=for-the-badge\&logo=visual-studio-code\&logoColor=white)

---

## 🌟 Featured Project

### 🪑 **Furniture Website** (Ongoing)

A modern, responsive furniture store website using **HTML, CSS, JavaScript**.

* 🏠 Elegant and clean homepage
* 🛋️ 3×3 Product Grid Display
* 🧾 Order Management System
* 🖼 Product Preview Page
* 💳 Checkout Flow (Upcoming)

---

## 🐍 GitHub Contribution Snake

name: Generate Snake

on:
  workflow_dispatch:
  schedule:
    - cron: '0 */6 * * *'   # runs every 6 hours
  push:
    branches:
      - main

jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - name: Checkout
        uses: actions/checkout@v4
        with:
          persist-credentials: false

      - name: Generate snake from contribution graph
        uses: fabiospampinato/github-contribution-grid-snake-action@v1
        with:
          username: 'Jegan-005'
          repo: 'Jegan-005'
          path: 'output/github-contribution-grid-snake.svg'
          # optionally set cols/rows/scale if supported by action
          
      - name: Commit SVG
        run: |
          git config user.name "github-actions[bot]"
          git config user.email "41898282+github-actions[bot]@users.noreply.github.com"
          git add output/github-contribution-grid-snake.svg || true
          git commit -m "Update contribution snake" || echo "Nothing to commit"
          git push origin HEAD:main || true


---

## 🏆 Trophies & Achievements

<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=Jegan-005&theme=radical&no-frame=true&row=1&column=6" />
</p>
<img src="https://github-readme-stats.vercel.app/api?username=Jegan-005&show_icons=true&theme=tokyonight" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Jegan-005&layout=compact&theme=tokyonight" />


---

## ⚙️ GitHub Analytics

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Jegan-005&show_icons=true&theme=tokyonight" height="165" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Jegan-005&layout=compact&theme=tokyonight" height="165" />
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=Jegan-005&style=for-the-badge&color=brightgreen" />
</p>

---

## 🔥 Highlights

* 🚀 Strong tech + leadership presence
* 🔧 Full-stack development journey
* 📚 Continually improving coding skills
* 🧠 Logical thinker & problem solver


---

## 📫 Connect With Me

<p align="center">
  <a href="mailto:kit27.csbs24@gmail.com"><img src="https://img.shields.io/badge/Email-D14836.svg?style=for-the-badge&logo=gmail&logoColor=white" /></a>
  <a href="https://linkedin.com/in/jegan-s23/"><img src="https://img.shields.io/badge/LinkedIn-0077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="https://github.com/Jegan-005"><img src="https://img.shields.io/badge/GitHub-181717.svg?style=for-the-badge&logo=github&logoColor=white" /></a>
  <a href="https://codolio.com/profile/jegan_"><img src="https://img.shields.io/badge/Codolio-000000.svg?style=for-the-badge&logo=codeforces&logoColor=white" /></a>
</p>

---

### 💬 Quote

> "First, solve the problem. Then, write the code." – John Johnson

<p align="center">
  <i>✨ Always exploring new technologies and improving one line of code at a time ✨</i>
</p>
