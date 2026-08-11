# Vic-Box GitHub Pages Site

Esta pasta contém a versão pronta para publicar como site estático no GitHub Pages.

## Estrutura
- `index.html` - página principal do site.
- `pages/` - outras páginas HTML copiadas do projeto.
- `css/styles.css` - estilos globais da landing page.
- `assets/` - imagens usadas pelos HTML.
- `.nojekyll` - garante que o GitHub Pages não ignore arquivos ou pastas com underscore.

## Como publicar
1. Crie um repositório no GitHub.
2. Faça commit de todo o conteúdo da pasta `github-pages`.
3. No GitHub, vá em `Settings` > `Pages`.
4. Selecione `Deploy from a branch` e escolha a branch principal (`main` ou `master`).
5. Defina a pasta como `/github-pages` se usar `gh-pages` ou `/` se publicar diretamente do root do repositório.
6. Aguarde o deploy.

## Observações
- Se quiser usar apenas a pasta `github-pages` como site, basta apontar o GitHub Pages para ela.
- Já há `index.html` na raiz da pasta e links relativos prontos para `css/styles.css` e `assets/`.
