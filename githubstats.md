# Blocos para personalizar o GitHub

Este arquivo guarda os blocos principais usados no `README.md` do perfil. O projeto de referencia e o [github-readme-stats](https://github.com/anuraghazra/github-readme-stats), que gera cards dinamicos para estatisticas, linguagens e repositorios.

> Observacao: em 11 de maio de 2026, o endpoint publico `https://github-readme-stats.vercel.app/api` estava retornando `503 DEPLOYMENT_PAUSED`. Por isso o `README.md` usa cards alternativos que estavam funcionando na verificacao local. Os blocos abaixo ficam prontos para usar quando o endpoint publico voltar ou quando voce tiver um deploy proprio do `github-readme-stats`.

## Tags de identidade

```md
<p align="center">
  <a href="https://IdeiaSpace.com">
    <img src="https://img.shields.io/badge/IdeiaSpace-Educacao%20Espacial-111827?style=for-the-badge" alt="IdeiaSpace Educacao Espacial" />
  </a>
  <img src="https://img.shields.io/badge/Foco-Space%20Tech-2f80ed?style=for-the-badge" alt="Foco em Space Tech" />
  <img src="https://img.shields.io/badge/Embarcados-ESP32%20%2B%20Arduino%20CLI-16a34a?style=for-the-badge" alt="ESP32 e Arduino CLI" />
  <a href="https://tleideiaspaceview.vercel.app">
    <img src="https://img.shields.io/badge/Satelites-Monitoramento%20em%20tempo%20real-7c3aed?style=for-the-badge" alt="Monitoramento de satelites em tempo real" />
  </a>
</p>
```

## Tags de stack

```md
<p align="center">
  <img src="https://img.shields.io/badge/HTML5-e34f26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
  <img src="https://img.shields.io/badge/CSS3-1572b6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" />
  <img src="https://img.shields.io/badge/JavaScript-f7df1e?style=for-the-badge&logo=javascript&logoColor=111827" alt="JavaScript" />
  <img src="https://img.shields.io/badge/TypeScript-3178c6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/React-20232a?style=for-the-badge&logo=react&logoColor=61dafb" alt="React" />
  <img src="https://img.shields.io/badge/Arduino_CLI-00979d?style=for-the-badge&logo=arduino&logoColor=white" alt="Arduino CLI" />
  <img src="https://img.shields.io/badge/ESP32-e7352c?style=for-the-badge&logo=espressif&logoColor=white" alt="ESP32" />
  <img src="https://img.shields.io/badge/C%2B%2B-00599c?style=for-the-badge&logo=cplusplus&logoColor=white" alt="C++" />
  <img src="https://img.shields.io/badge/IoT-0f766e?style=for-the-badge" alt="IoT" />
  <img src="https://img.shields.io/badge/Satellite_Tracking-312e81?style=for-the-badge" alt="Satellite Tracking" />
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white" alt="Node.js" />
  <img src="https://img.shields.io/badge/Python-3776ab?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169e1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/Git-f05032?style=for-the-badge&logo=git&logoColor=white" alt="Git" />
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
</p>
```

## Midias digitais

Troque `SEU_INSTAGRAM` e `SEU_ID_DO_DISCORD` pelos seus dados reais.

```md
<p align="center">
  <a href="https://www.instagram.com/SEU_INSTAGRAM/">
    <img src="https://img.shields.io/badge/Instagram-Contato-e4405f?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram" />
  </a>
  <a href="https://discord.com/users/SEU_ID_DO_DISCORD">
    <img src="https://img.shields.io/badge/Discord-Contato-5865f2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" />
  </a>
  <a href="https://www.linkedin.com/in/luis-zarbielli/">
    <img src="https://img.shields.io/badge/LinkedIn-Luis%20Zarbielli-0a66c2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn Luis Zarbielli" />
  </a>
</p>
```

## Cards de estatisticas

```md
<p align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=ZarbL&show_icons=true&theme=transparent&hide_border=true&include_all_commits=true&count_private=true&rank_icon=github" alt="Estatisticas do GitHub de Luis Zarbielli" />
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=ZarbL&layout=compact&theme=transparent&hide_border=true&langs_count=8" alt="Linguagens mais usadas por Luis Zarbielli" />
</p>
```

## Cards alternativos usados no README

```md
<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=ZarbL&theme=transparent" alt="Resumo do perfil GitHub de Luis Zarbielli" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com?user=ZarbL&theme=transparent&hide_border=true&locale=pt_BR" alt="Sequencia de contribuicoes no GitHub" />
</p>

<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=ZarbL&theme=flat&no-frame=true&margin-w=8" alt="Trofeus do perfil GitHub de Luis Zarbielli" />
</p>
```

## commits

O `README.md` usa os SVGs gerados pela action em `.github/workflows/snake.yml`. Depois de subir para o GitHub, rode a action manualmente em `Actions > Generate snake animation > Run workflow`.

```md
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/ZarbL/ZarbL/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/ZarbL/ZarbL/output/github-contribution-grid-snake.svg" />
  <img alt="Animacao da cobrinha comendo os commits de Luis Zarbielli" src="https://raw.githubusercontent.com/ZarbL/ZarbL/output/github-contribution-grid-snake.svg" />
</picture>
```

## Card de repositorio

Para destacar outro projeto, troque o valor de `repo=ZarbL` pelo nome do repositorio.

```md
<p align="center">
  <a href="https://github.com/ZarbL/ZarbL">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=ZarbL&repo=ZarbL&theme=transparent&hide_border=true" alt="Repositorio de perfil ZarbL" />
  </a>
</p>
```
