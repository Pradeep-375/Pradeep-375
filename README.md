<h1 align="center">👋 Hi, I'm Pradeep</h1>

<h3 align="center">
Aspiring Software Developer | Java | SQL | DSA
</h3>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=Pradeep-375&label=Profile%20Views&style=flat" />
</p>

---

## 👨‍💻 About Me

- 🎓 Computer Science Engineering student
- ☕ Learning Java and Object-Oriented Programming
- 🗄️ Practicing SQL and Database Management
- 🧠 Improving Data Structures & Algorithms
- 💻 Solving problems on LeetCode
- 🌐 Interested in Web Development
- 🚀 Building real-world projects

---

## 🚀 Currently Exploring

- ☕ Advanced Java
- 🌱 Spring Boot
- 🗄️ SQL
- 🧠 Data Structures & Algorithms
- 🌐 Full Stack Development
- ☁️ Cloud Technologies

---

## 🎯 2026 Goals

- [ ] Solve 300+ LeetCode problems
- [ ] Improve Data Structures & Algorithms
- [ ] Build 3+ real-world projects
- [ ] Learn Spring Boot
- [ ] Improve SQL skills
- [ ] Contribute to Open Source
- [ ] Get a Software Developer role

---
## 🛠️ Tech Stack

### 💻 Programming Languages

<p>
<img src="https://skillicons.dev/icons?i=java,python,js" />
</p>

### 🌐 Web Development

<p>
<img src="https://skillicons.dev/icons?i=html,css,bootstrap,nodejs,express" />
</p>

### 🗄️ Databases

<p>
<img src="https://skillicons.dev/icons?i=mysql,mongodb" />
</p>

### 🔧 Tools

<p>
<img src="https://skillicons.dev/icons?i=git,github,vscode,idea" />
</p>
---

## 💻 LeetCode

<p align="center">
  <img src="https://leetcard.jacoblin.cool/PradeepMedaboina?theme=dark&font=baloo&ext=contest" />
</p>
---

## 📊 GitHub Statistics

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Pradeep-375&show_icons=true&theme=tokyonight" />
</p>
<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Pradeep-375&layout=compact&theme=tokyonight" />
</p>
---

## 🔥 GitHub Streak

<p align="center">
  <img src="https://streak-stats.demolab.com?user=Pradeep-375&theme=tokyonight" />
</p>
---

## 📈 Contribution Activity

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=Pradeep-375&theme=tokyo-night" />
</p>
---

## 🚀 Featured Projects

### 🔐 Smart Code Plagiarism Detector

A web application that detects similarities between source codes and
generates plagiarism reports.

**Tech Stack:** Python, Flask, MySQL, Scikit-learn

🔗 [View Project](https://github.com/Pradeep-375/YOUR-REPOSITORY-NAME)


### 📷 LensHub

A camera rental and selling platform with booking and order management.

**Tech Stack:** HTML, CSS, JavaScript, Node.js, MongoDB

🔗 [View Project](https://github.com/Pradeep-375/YOUR-REPOSITORY-NAME)


### ☕ Java Projects

Collection of Java programming and problem-solving projects.

**Tech Stack:** Java, OOP, DSA

🔗 [View Project](https://github.com/Pradeep-375/YOUR-REPOSITORY-NAME)
---

## 🏆 Achievements

- 💻 Solved programming problems on LeetCode
- 🧠 Practicing Data Structures & Algorithms
- 🚀 Built academic and personal projects
- 📚 Completed technical certifications
- 👨‍💻 Maintaining active GitHub repositories

  name: Generate Snake

on:
  schedule:
    - cron: "0 0 * * *"
  workflow_dispatch:

jobs:
  generate:
    runs-on: ubuntu-latest

    steps:
      - uses: Platane/snk@v3
        with:
          github_user_name: ${{ github.repository_owner }}
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark

      - uses: crazy-max/ghaction-github-pages@v4
        with:
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
          BUILD_DIR: dist

          ---

## 🐍 Contribution Snake

<p align="center">
  <img src="https://raw.githubusercontent.com/Pradeep-375/Pradeep-375/output/github-contribution-grid-snake.svg" />
</p>
