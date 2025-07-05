<p align="center">
  <img src="https://raw.githubusercontent.com/AkshitTiwarii/assets/main/galaxy-banner.gif" width="100%" alt="Galaxy background with animated comet"/>
</p>

<h1 align="center">Hi, I’m <a href="https://github.com/AkshitTiwarii">Akshit Tiwari</a> 👋</h1>
<h3 align="center">B.Tech • Android Dev • Geo‑AI Enthusiast • Open‑Source Contributor (GSSoC’25)</h3>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=AkshitTiwarii&style=flat-square" alt="Profile views"/>
  <img src="https://img.shields.io/github/followers/AkshitTiwarii?label=Follow&style=social" alt="GitHub followers"/>
  <img src="https://img.shields.io/badge/📫%20Reach%20Me-akshittiwarii%40gmail.com-blue" alt="Email"/>
</p>

---

## 🚀 Projects I'm Proud Of

### 🛰️ **Geospatial Help‑Bot for Satellite Data**
- A RAG-powered chatbot that answers satellite & meteorological queries with live maps and source citations.
- Hybrid retrieval: FAISS + BM25 + Knowledge Graph + LLM generation.
- Built with Python · Streamlit · Neo4j · GPT‑3.5/DeepSeek · Folium.
- ✅ 92% intent accuracy · Avg 1.7s response time.
- 🧠 View Demo: [![](https://img.youtube.com/vi/xDB5joiAe3Q/0.jpg)](https://youtu.be/xDB5joiAe3Q)

### 🛠️ **Android MVVM Shopping App**
- Offline Kotlin application using Room DB and Jetpack Architecture Components.

### 🧱 **RAG Chatbot Contribution**
- Authored an Open Source chatbot powered by LangChain & FastAPI as part of GSSoC’25.

---

## 💻 Tech Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=py,kotlin,java,cpp,js,react,androidstudio,git,docker,linux&perline=7" />
</p>

---

## 📊 GitHub Stats

![Akshit's GitHub activity graph](https://github-readme-activity-graph.cyclic.app/graph?username=AkshitTiwarii&theme=react-dark)


---

## ✨ Fun Spotlight

<p align="center">
  <img src="https://raw.githubusercontent.com/AkshitTiwarii/assets/main/quote-gen.gif" alt="Random inspiration" width="600"/>
</p>

_A random motivational quote loads every time you refresh your profile – because code and inspiration go hand in hand._

---

## 📡 Let's Connect

<p align="center">
  <a href="https://www.linkedin.com/in/akshit-tiwarii"><img src="https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:akshittiwarii@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836.svg?logo=gmail&logoColor=white" alt="Gmail"/></a>
</p>

![3D Skyline](https://raw.githubusercontent.com/AkshitTiwarii/AkshitTiwarii/output/profile-3d-contrib/profile-night-rainbow.svg)


---

### 🛠 One-Time Setup (Optional)

<details>
<summary>⚙️ Add 3D Contribution Skyline</summary>
  
Add a GitHub Action in `.github/workflows/3d.yml`:
```yaml
name: Build 3D Skyline
on:
  schedule:
    - cron: '0 0 * * *'
jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - uses: Platane/snk/svg-only@v3
        with:
          github_user_name: AkshitTiwarii
          outputs: |
            output/profile-3d-contrib/profile-night.svg
