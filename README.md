<h1 align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=28&pause=1000&color=58A6FF&center=true&vCenter=true&width=600&lines=Hi+%F0%9F%91%8B%2C+I'm+Havyn+Liew;Web+Developer+%F0%9F%92%BB;Security+Enthusiast+%F0%9F%9B%A1%EF%B8%8F;CTF+Player+%F0%9F%8F%B4" alt="Typing SVG" />
</h1>

<h3 align="center">A passionate Web Developer & Security Enthusiast from Malaysia 🇲🇾</h3>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=TalonExe&label=Profile%20views&color=0e75b6&style=flat" alt="profile views" />
  <img src="https://img.shields.io/github/followers/TalonExe?label=Followers&style=flat&color=0e75b6" alt="followers" />
</p>

---

## 🧑‍💻 About Me

- 🔭 Currently building **secure, full-stack web applications**
- 🌱 Learning **Rust & Systems Security**
- 🏆 Actively competing in **CTF challenges** (web, crypto, pwn)
- 💬 Ask me about **React, Node.js, PostgreSQL, or web security**
- 📫 Reach me at **[LinkedIn](https://linkedin.com/in/havyn-liew)**
- ⚡ Fun fact: I break things to understand how they work

---

## 🏆 GitHub Trophies

<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=TalonExe&theme=algolia&no-frame=true&no-bg=true&margin-w=4&row=1" alt="trophies" />
</p>

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=TalonExe&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true" height="170" alt="stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=TalonExe&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" height="170" alt="top languages" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=TalonExe&theme=tokyonight&hide_border=true" alt="streak stats" />
</p>

---

## 🐍 Contribution Snake

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/TalonExe/TalonExe/output/github-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/TalonExe/TalonExe/output/github-snake.svg" />
    <img alt="contribution snake" src="https://raw.githubusercontent.com/TalonExe/TalonExe/output/github-snake.svg" />
  </picture>
</p>

> ⚠️ The snake requires a one-time GitHub Actions setup — see instructions below.

---

## 🛠️ Tech Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)

**Frontend**

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Svelte](https://img.shields.io/badge/Svelte-FF3E00?style=for-the-badge&logo=svelte&logoColor=white)

**Backend & Database**

![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)

**DevOps & Tools**

![Docker](https://img.shields.io/badge/Docker-2CA5E0?style=for-the-badge&logo=docker&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

**Security**

![Kali Linux](https://img.shields.io/badge/Kali_Linux-557C94?style=for-the-badge&logo=kalilinux&logoColor=white)
![Burp Suite](https://img.shields.io/badge/Burp_Suite-FF6633?style=for-the-badge&logo=burpsuite&logoColor=white)
![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=for-the-badge&logo=wireshark&logoColor=white)

---

## 🤝 Connect with Me

<p align="left">
  <a href="https://linkedin.com/in/havyn-liew" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="https://github.com/TalonExe" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  </a>
</p>

---

<details>
<summary>⚙️ <b>How to set up the contribution snake</b></summary>
<br>

1. In your profile repo (`TalonExe/TalonExe`), create the file `.github/workflows/snake.yml`
2. Paste this into it:

```yaml
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
          github_user_name: TalonExe
          outputs: |
            dist/github-snake.svg
            dist/github-snake-dark.svg?palette=github-dark
      - uses: crazy-max/ghaction-github-pages@v3
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
```

3. Go to **Actions** tab → run the workflow manually once → the snake SVG will appear on your profile.

</details>
