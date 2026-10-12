# WODBOX · MVP

Gestão e engajamento para boxes de cross. Esta versão roda só com dados de demonstração, salvos no navegador (localStorage).

- `index.html`: o app inteiro (lado atleta e lado gestão), sem build.
- `manifest.webmanifest` e `sw.js`: instalação na tela inicial e cache offline.
- Links diretos: `?role=atleta` ou `?role=gestao`, com `&tab=` (hoje, feed, explorar, ranking, perfil / painel, wod, turmas, alunos, fin), `&scope=` no feed (box, seguindo, explorar) e `&rank=` no ranking (rx, sc, br, ev, tm, xp).
- Camada social: identidade global do atleta, seguir, feed Meu box / Seguindo / Explorar, 4 boxes fictícios, ranking Brasil, recap semanal, convites.
- Publicado em https://vibesadm2025-cmyk.github.io/wodbox/

## Rodar localmente

Abra `index.html` no navegador, ou sirva a pasta com qualquer servidor estático:

```
python3 -m http.server 8080
```

## Deploy

Estático. Funciona em GitHub Pages, Vercel ou qualquer hospedagem de arquivos.
