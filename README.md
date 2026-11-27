# Curso de Gestão de Tráfego Pago 2026 — NeexFlow

Curso em 15 unidades e 3 níveis (Fundamentos, Intermediário, Avançado). Cada unidade tem teoria, exemplo com números e prática real. Inclui glossário com busca, simulado comentado (38 questões) e 43 referências numeradas, conferidas em 26/11/2026.

Site estático de arquivo único (`index.html`), sem build. Progresso, tema e respostas do simulado ficam no `localStorage` do navegador.

## Publicar no GitHub Pages

O repositório precisa ser **público** (no plano gratuito, o Pages não funciona com repositório privado).

```bash
git init -b main
git add .
git commit -m "Curso de Gestão de Tráfego 2026 v1.0"
git remote add origin https://github.com/sergiolemoscarvalho/curso-gestao-trafego.git
git push -u origin main
```

Depois: Settings → Pages → Deploy from a branch → `main` / `(root)` → Save.

## Atualizar o conteúdo

1. Edite `index.html`.
2. Acrescente a versão no array `VERSIONS` (no script, perto do início) — ela aparece no banner de novidades e no histórico.
3. Registre a mudança no `CHANGELOG.md`.
4. Reconfira as fontes da seção Referências pelo menos a cada trimestre e atualize a data "Fontes conferidas em".
