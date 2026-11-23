# Roadmap Gestor de Tráfego 2026 — NeexFlow

Curso de gestão de tráfego em 3 níveis (Fundamentos, Intermediário, Avançado), com fontes oficiais conferidas em 23/11/2026.

É um site estático de arquivo único (`index.html`). Não precisa de build nem de dependências: só usa Google Fonts.

## Publicar no GitHub Pages

```bash
git init
git add .
git commit -m "Roadmap Gestor de Tráfego 2026"
git branch -M main
git remote add origin git@github.com:sergiolemoscarvalho/roadmap-gestor-trafego.git
git push -u origin main
```

Depois, no GitHub: **Settings → Pages → Build and deployment → Source: Deploy from a branch → `main` / `(root)` → Save**.

O site fica em `https://sergiolemoscarvalho.github.io/roadmap-gestor-trafego/`.

### Domínio próprio (opcional)

Para usar, por exemplo, `trafego.neexflow.com.br`:

1. Crie um arquivo `CNAME` na raiz com o conteúdo `trafego.neexflow.com.br`.
2. No DNS, crie um registro CNAME `trafego` apontando para `sergiolemoscarvalho.github.io`.
3. Em Settings → Pages, informe o domínio e marque **Enforce HTTPS**.

## Identidade visual

- Fundo `#050a1e`: cor de tema oficial do neexflow.com.br.
- Logo: carregado de `https://www.neexflow.com.br/logobg-b.svg`. Se preferir não depender do site principal, copie o SVG para `assets/logo.svg` e troque o `src` da tag `<img>`.
- **Cor de destaque (`--acc`) é provisória** (`#58a6ff`). Troque pelo hex oficial da marca no bloco `:root` do CSS.

## Manutenção do conteúdo

Plataformas de anúncio mudam rápido. Reconfira as fontes da aba "Fontes" pelo menos uma vez por trimestre e atualize a data "Fontes conferidas em".
