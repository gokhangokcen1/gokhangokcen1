<h1 align="center">Hi, I'm Gökhan 👋</h1>

<p align="center">
  Electrical-electronics engineer who likes to understand systems from the bottom up:<br>
  network protocols, machine learning pipelines, and the low-level machinery underneath them.
</p>

<p align="center">
  <a href="https://gokhangokcen1.github.io"><img src="https://github.com/gokhangokcen1/gokhangokcen1.github.io/raw/main/pics/shakespeare.png" alt="Portfolio" width=50</a>
  <a href="https://www.linkedin.com/in/gokhangokcen"><img src="https://github.com/dheereshag/coloured-icons/blob/master/public/logos/social%20media/linkedin/linkedin.svg" alt="LinkedIn" width=40></a>
  <a href="mailto:gokcenngokhan@gmail.com"><img src="https://github.com/dheereshag/coloured-icons/blob/master/public/logos/technology/gmail/gmail.svg" alt="Email" width=40></a>
</p>


---

## 🧭 About me

- 🎓 Electrical-electronics engineering graduate
- 🧠 Train deep learning models for text and audio classification
- 📖 I learn mechanism first, then build. I publish my notes and resources along the way

---

## 🚀 Projects

### 🛡️ [Intrusion Detection System](https://github.com/gokhangokcen1/intrusion-detection-system)
A rule-based IDS/IPS with a live dashboard.
- Captures live traffic, flags TCP SYN scans and traffic to sensitive ports, stores packets and alerts in SQLite
- Can block sources through **Windows Firewall**, verifies each rule was really applied, retries failures and detects drift
- Automatic 15-minute blocks for high-severity port scans, run outside the capture loop so capture never stalls

`Go` `Fiber` `Vue 3` `SQLite` `Npcap`

### 🧰 [Cybersecurity Internship Projects](https://github.com/gokhangokcen1/cybersecurity-intern)
What I built during my internship while learning Go: a student management **CRUD app** (Fiber + GORM + PostgreSQL + Vue) and a networking tool suite.
- Subnet calculator, port checker (single and bulk with mail report), IP scanner, SSL checker
- Packet sniffer and analyzer, packet sender (custom TCP/UDP), DNS and Whois checkers, SMTP mail sender

`Go` `Fiber` `GORM` `PostgreSQL` `Vue`

### 🌐 [Categorify TR: Website Classifier](https://github.com/gokhangokcen1/AI-Website-Classifier)
Classifies Turkish websites into 16 categories.
- Pages collected with Crawl4AI, labels derived from the Curlie taxonomy
- Fine-tuned **XLM-RoBERTa** (PyTorch)
- Go/Fiber API, model server and Vue interface on top

`Python` `PyTorch` `XLM-RoBERTa` `Go` `Vue`

### 🫁 [Audio-Based Asthma Detection](https://github.com/gokhangokcen1/Audio-Based-Asthma-Detection)
End-to-end deep learning system that tells asthma from healthy cough sounds.
- Pipeline: 16 kHz audio → energy-based segmentation → 3 s windows → Mel-spectrograms → **CNN + BiGRU** → majority vote
- **92.58% test accuracy**, F1 0.911, on 1,144 recordings

`Python` `PyTorch` `Librosa` `Deep Learning`

### 🎾 [Tennis Ball Collecting Robot](https://github.com/gokhangokcen1/tennis-bot)
A ROS 2 (Humble) robot that finds and collects tennis balls using classic computer vision.
- **HSV color masking in OpenCV**, chosen on purpose to keep cost low
- Greedy nearest-neighbor collection and court-half navigation
- Packages: `bringup` · `description` · `perception` · `navigation`

`ROS 2` `OpenCV` `Python` `URDF`

### 📚 [Cyber Security Roadmap](https://github.com/gokhangokcen1/cyber-security-roadmap) ![Stars](https://img.shields.io/github/stars/gokhangokcen1/cyber-security-roadmap?style=social)
A curated list of cybersecurity certifications and the best free resources for each: networking, pentesting, defensive security, cryptography, and hands-on practice platforms.

### 🖥️ [KIRAT-OS](https://github.com/gokhangokcen1/KIRAT-OS)
Notes and solutions while building a computer from scratch with **nand2tetris**. Read the notes on my [blog](https://gokhangokcen1.github.io/blog/kirat-os).

---

## 🛠️ Tech I work with

![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Vue](https://img.shields.io/badge/Vue.js-4FC08D?style=flat-square&logo=vuedotjs&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![ROS 2](https://img.shields.io/badge/ROS_2-22314E?style=flat-square&logo=ros&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![C](https://img.shields.io/badge/C-Programming%20Language-brightgreen)
![ESP32](https://img.shields.io/badge/ESP--IDF-%E2%89%A56.0-orange)


---
<!--
## 📊 GitHub stats

<p align="center">
  <img height="160" src="https://github-readme-stats.vercel.app/api?username=gokhangokcen1&show_icons=true&hide_border=true&count_private=true" alt="GitHub stats">
  <img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=gokhangokcen1&layout=compact&hide_border=true" alt="Top languages">
</p>
-->
