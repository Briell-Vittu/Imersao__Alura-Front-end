# Spotify — réplica de interface (projeto de estudo)

> Projeto de estudo feito na **Imersão Front-End da Alura**: réplica da página inicial do Spotify, com pesquisa de artistas a partir de uma API local.

**[▶ Ver o projeto a funcionar](https://briell-vittu.github.io/Imersao__Alura-Front-end/)**

## O que pratiquei

- **HTML semântico** e organização da página em secções
- **CSS** com Flexbox e Grid, layout responsivo e estados de hover
- **JavaScript** para a pesquisa de artistas: leitura do campo de pesquisa, `fetch` a uma API e atualização do DOM
- **API local com json-server** a servir os dados dos artistas

## Estrutura

```
imersão front end-alura/
├── index.html      # página principal
├── script.js       # pesquisa de artistas
├── src/            # estilos e imagens
└── api-artists/    # dados para o json-server
```

## Como correr localmente

A pesquisa usa o json-server na versão **0.17.4**:

```bash
npm install -g json-server@0.17.4
cd "imersão front end-alura/api-artists"
json-server --watch artists.json --port 3000
```

Depois abra `imersão front end-alura/index.html` no navegador.

## Nota

Projeto educativo, sem fins comerciais. Spotify é uma marca registada da Spotify AB; esta réplica serve apenas para praticar HTML, CSS e JavaScript.

---

Feito por **Victor Gabriel** · [LinkedIn](https://www.linkedin.com/in/victor-gabriel-devops) · [GitHub](https://github.com/Briell-Vittu)
