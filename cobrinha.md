# Cobrinha comendo commits

Este repositorio usa a action `Platane/snk/svg-only@v3` para gerar a animacao da cobrinha a partir do grafico de contribuicoes do GitHub.

## Como funciona

1. O workflow `.github/workflows/snake.yml` roda todos os dias meia-noite UTC.
2. Ele tambem pode ser executado manualmente pelo GitHub em `Actions > Generate snake animation > Run workflow`.
3. A action gera dois arquivos:
   - `github-contribution-grid-snake.svg`
   - `github-contribution-grid-snake-dark.svg`
4. Esses arquivos sao publicados automaticamente na branch `output`.
5. O `README.md` carrega a animacao direto da branch `output`.

## Bloco usado no README

```md
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/ZarbL/ZarbL/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/ZarbL/ZarbL/output/github-contribution-grid-snake.svg" />
  <img alt="Animacao da cobrinha comendo os commits de Luis Zarbielli" src="https://raw.githubusercontent.com/ZarbL/ZarbL/output/github-contribution-grid-snake.svg" />
</picture>
```

## Observacao

Na primeira vez, a imagem so aparece depois que o workflow for executado no GitHub e a branch `output` for criada.
