# WODBOX · MVP

Gestão e engajamento para boxes de cross. Esta versão roda só com dados de demonstração, salvos no navegador (localStorage).

- `index.html`: o app inteiro (lado atleta e lado gestão), sem build.
- `manifest.webmanifest` e `sw.js`: instalação na tela inicial e cache offline.
- Links diretos: `?role=atleta` abre no lado atleta, `?role=gestao` no lado gestão.

## Rodar localmente

Abra `index.html` no navegador, ou sirva a pasta com qualquer servidor estático:

```
python3 -m http.server 8080
```

## Deploy

Estático. Funciona em GitHub Pages, Vercel ou qualquer hospedagem de arquivos.
