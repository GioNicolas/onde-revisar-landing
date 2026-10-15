# Onde Revisar Primeiro — landing page

Página de apresentação do estudo [pesquisa-onde-revisar](https://github.com/GioNicolas/pesquisa-onde-revisar): sinais da trajetória de agentes de código para priorizar a revisão de diffs.

Site estático em um único arquivo (`index.html`), sem build e sem dependências.

## Rodar localmente

Abra `index.html` no navegador, ou sirva a pasta:

```
python -m http.server 8000
```

## Deploy na Vercel

Importe este repositório na Vercel. Em *Framework Preset* escolha **Other**, deixe *Build Command* e *Output Directory* vazios. A Vercel serve o `index.html` da raiz.
