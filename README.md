# Olá, eu sou Luan Prates
👀 Tenho interesse em Desenvolvimento de Software e Desenvolvimento Web.
🌱 Atualmente estou aprendendo Javascript.
💞️ Estou procurando colaborar em projetos open-source e iniciativas de aprendizado de máquina.
📫 Como me contactar: meu email é luanpratesk2@gmail.com ou conecte-se comigo no LinkedIn https://www.linkedin.com/in/luan-prates-25557519b/
⚡ Curiosidade: Adoro programar enquanto ouço música.

 <a href "https://github.com/LuanPrates-1/LuanPrates-1/edit/main/README.md">

<div>

![](https://github-readme-stats.vercel.app/api?username=LuanPrates-1)
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=anuraghazra)](https://github.com/anuraghazra/github-readme-stats)
</div>
<div>
 name: Generate Datas

on:
  schedule: # execute every 12 hours
    - cron: "* */12 * * *"
  workflow_dispatch:

jobs:
  build:
    name: Jobs to update datas
    runs-on: ubuntu-latest
    steps:
      # Snake Animation
      - uses: Platane/snk@master
        id: snake-gif
        with:
          github_user_name: rafaballerini
          svg_out_path: dist/github-contribution-grid-snake.svg

      - uses: crazy-max/ghaction-github-pages@v2.1.3
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
  
</div>
