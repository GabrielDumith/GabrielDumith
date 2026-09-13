<h1 align="center">Olá! Sou Gabriel Dumith 👋</h1>

<p align="center">
  Desenvolvedor apaixonado por tecnologia, sempre aprendendo e construindo coisas novas.
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=GabrielDumith&label=Visualizações+do+perfil&color=blueviolet&style=flat" alt="visitor badge" />
</p>

---

### 🛠️ Tecnologias que utilizo

<div align="center">
  <img alt="JavaScript" height="40" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg">
  <img alt="Bootstrap" height="40" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/bootstrap/bootstrap-original.svg">
  <img alt="HTML5" height="40" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg">
  <img alt="CSS3" height="40" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg">
  <img alt="C" height="40" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/c/c-original.svg">
  <img alt="React" height="40" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg">
  <img alt="Git" height="40" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg">
  <img alt="Python" height="40" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg">
  <img alt="Java" height="40" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg">
  <img alt="SQL" height="40" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg">
  <img alt="MariaDB" height="40" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mariadb/mariadb-original.svg">
</div>

---

### 📊 Estatísticas do GitHub

name: Generate Snake Animation

on:
  schedule:
    - cron: "0 */12 * * *" # Atualiza a cada 12 horas
  workflow_dispatch:

jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v3

      - uses: Platane/snk@v3
        with:
          github_user_name: GabrielDumith
          outputs: |
            dist/github-snake.svg
            dist/github-snake-dark.svg?palette=github-dark

      - uses: crazy-max/ghaction-github-pages@v3.1.0
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}

### 📫 Conecte-se comigo

<div align="center">
  <a href="mailto:seuemail@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="gmail">
  </a>
  <a href="https://www.instagram.com/biel_dumith/">
    <img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="instagram">
  </a>
  <a href="https://www.linkedin.com/in/seu-usuario/">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="linkedin">
  </a>
</div>
