# Site da Dra. Mayara Cardoso

Site institucional estatico em portugues para a Dra. Mayara Cardoso, hematologista em Santos-SP.

O projeto usa apenas HTML e CSS. Nao ha servidor, banco de dados, framework JavaScript, Worker ou etapa obrigatoria de build.

## Estrutura

- `site/index.html`: pagina unica do site.
- `site/assets/styles.css`: estilos do site.
- `site/images/`: imagens publicas em WebP usadas pelo site, rastreadas por Git LFS.
- `site/favicon.svg`: favicon em vinho e dourado.
- `.github/workflows/deploy-github-pages.yml`: publicacao automatica no GitHub Pages.
- `PERSONALIZACAO.md`: checklist para trocar textos, contatos e imagens da Dra. Mayara.

## Conteudo atual

A pagina inclui:

- Hero com chamada principal e botoes para Doctoralia e WhatsApp.
- Cards de destaque para anemia, hemograma, vitaminas/pos-bariatrica e saude metabolica.
- Sobre mim em blocos.
- Galeria com as 9 imagens profissionais em WebP.
- Formacao academica.
- Diferenciais.
- Areas de atuacao.
- Como funciona a consulta.
- Depoimentos com links para Doctoralia e Google.
- Blog com temas sugeridos.
- FAQ.
- Rodape com endereco, redes sociais, Doctoralia, Google Maps, LGPD, CRM e RQE.

## Visualizar localmente

Abra este arquivo no navegador:

```txt
site/index.html
```

## Deploy no GitHub Pages

1. Envie as mudancas para a branch `main`.
2. O workflow `Deploy GitHub Pages` publicara a pasta `site` automaticamente.
3. Acompanhe o resultado em `Actions` no GitHub.

Como todos os caminhos sao relativos, o site funciona em enderecos como:

```txt
https://usuario.github.io/nome-do-repositorio/
```

Tambem funciona com dominio proprio configurado no GitHub Pages.

## Deploy no Cloudflare Pages

Ao criar o projeto no Cloudflare Pages:

- Framework preset: `None` ou `Static HTML`.
- Build command: deixe em branco ou use `exit 0`.
- Build output directory: `site`.
- Production branch: `main`.

O Cloudflare publicara o conteudo da pasta `site` em um dominio `*.pages.dev`.