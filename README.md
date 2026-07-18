# Site da Dra. Mayara Cardoso

Site institucional estatico em portugues para a Dra. Mayara Cardoso, hematologista.

O projeto usa apenas HTML e CSS. Nao ha servidor, banco de dados, framework JavaScript, Worker ou etapa obrigatoria de build.

## Estrutura

- `site/index.html`: pagina unica do site.
- `site/assets/styles.css`: estilos do site.
- `site/images/`: imagens publicas usadas pelo site.
- `site/favicon.svg`: favicon em vinho e dourado.
- `.github/workflows/deploy-github-pages.yml`: publicacao automatica no GitHub Pages.
- `PERSONALIZACAO.md`: checklist para trocar textos, contatos e imagens da Dra. Mayara.

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

## Antes de publicar

Atualize os dados reais da Dra. Mayara em `site/index.html`:

- CRM e RQE.
- Cidade, endereco e mapa.
- WhatsApp.
- Instagram.
- Foto profissional ou imagem do consultorio.
- Areas de atendimento confirmadas pela medica.
- Regras de convenio, particular ou reembolso.

Leia `PERSONALIZACAO.md` antes de publicar.