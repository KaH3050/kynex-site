# KYNEX

Site da KYNEX (agência de sites): HTML, CSS e JavaScript puros, sem build.

- `index.html` — o site inteiro
- `img/`, `favicon/` — imagens e ícones
- `_headers` — cabeçalhos de segurança e cache
- `wrangler.jsonc` — publicação na Cloudflare (arquivos estáticos desta pasta)

Cada envio (`git push`) para a branch `main` publica o site de novo na Cloudflare.
