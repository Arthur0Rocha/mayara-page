# Site da Dra. Mayara Cardoso

Site institucional estatico em portugues para a Dra. Mayara Cardoso, hematologista.

O projeto foi simplificado para usar apenas HTML e CSS. Nao ha servidor, banco de dados, framework JavaScript, Worker ou etapa obrigatoria de build.

## Estrutura

- `site/index.html`: versao principal do site.
- `site/versao-referencia/index.html`: versao visual alternativa.
- `site/assets/styles.css`: estilos das duas versoes.
- `site/images/`: imagens publicas usadas pelo site.
- `.github/workflows/deploy-github-pages.yml`: publicacao automatica no GitHub Pages.
- `PERSONALIZACAO.md`: checklist para trocar textos, contatos e imagens da Dra. Mayara.

## Visualizar localmente

Abra este arquivo no navegador:

```txt
site/index.html
```

Tambem e possivel abrir:

```txt
site/versao-referencia/index.html
```

## Deploy no GitHub Pages

1. Crie um repositorio no GitHub.
2. Envie este projeto para o repositorio.
3. No GitHub, acesse `Settings > Pages`.
4. Em `Build and deployment`, escolha `Source: GitHub Actions`.
5. Faca push para a branch `main`.
6. O workflow `Deploy GitHub Pages` publicara a pasta `site`.

Como todos os caminhos sao relativos, o site funciona em enderecos como:

```txt
https://usuario.github.io/nome-do-repositorio/
```

## Deploy no Cloudflare Pages

Ao criar o projeto no Cloudflare Pages:

- Framework preset: `None` ou `Static HTML`.
- Build command: deixe em branco ou use `exit 0`.
- Build output directory: `site`.
- Production branch: `main`.

O Cloudflare publicara o conteudo da pasta `site` em um dominio `*.pages.dev`.

## Antes de publicar

Atualize os dados reais da Dra. Mayara em `site/index.html` e `site/versao-referencia/index.html`:

- CRM e RQE.
- Cidade, endereco e mapa.
- WhatsApp.
- Instagram.
- Foto profissional ou imagem do consultorio.
- Areas de atendimento confirmadas pela medica.
- Regras de convenio, particular ou reembolso.

Leia `PERSONALIZACAO.md` antes de publicar.
