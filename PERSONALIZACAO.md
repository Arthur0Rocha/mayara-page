# Personalizacao do site

Use este checklist antes de publicar a versao final do site da Dra. Mayara.

## Dados principais

Atualize os dados em:

```txt
site/index.html
```

Dados atuais ja aplicados:

- CRM-SP 194309.
- RQE 87199.
- WhatsApp: (13) 4042-6210.
- Doctoralia: `https://www.doctoralia.com.br/mayara-cardoso/hematologista/aracaju`.
- Instagram: `https://www.instagram.com/dramayara.clinic/`.
- TikTok: `https://www.tiktok.com/@dramayara.clinic`.
- LinkedIn: `https://www.linkedin.com/in/mayara-cardoso-50a71523a/`.
- Endereco: Av. Conselheiro Nebias, 703 - Cj. 2102 - Boqueirao, Santos - SP, 11045-003.

## Imagens

As imagens aprovadas para publicação foram convertidas para WebP, renomeadas com nomes semânticos e publicadas em:

```txt
site/images/dra-mayara-cardoso-sobre.webp
site/images/dra-mayara-cardoso-atendimento-hematologia.webp
site/images/dra-mayara-cardoso-consultorio-santos-01.webp
site/images/dra-mayara-cardoso-consultorio-santos-02.webp
site/images/dra-mayara-cardoso-consultorio-santos-03.webp
site/images/dra-mayara-cardoso-retrato-profissional-01.webp
site/images/dra-mayara-cardoso-retrato-profissional-02.webp
site/images/dra-mayara-cardoso-retrato-profissional-03.webp
```

A foto principal usa `site/images/dra-mayara-cardoso-retrato-profissional-03.webp`. As demais imagens aprovadas aparecem na Galeria.

Os JFIF originais ficaram guardados localmente em `_rascunhos/imagens-originais-jfif/`, fora da publicação do site. A imagem `dra-mayara-cardoso-hero.webp` foi retirada de `site/images/` e mantida em `_rascunhos/imagens-nao-publicar/`, pois não deve ser publicada enquanto não houver liberação da Dra. Mayara.

As imagens publicadas são rastreadas por Git LFS. Ao trocar ou adicionar novas imagens, prefira WebP e mantenha nomes descritivos, sem espaços.

Para trocar alguma foto:

1. Coloque a nova imagem em `site/images/`.
2. Converta para WebP antes de publicar.
3. Atualize o caminho em `site/index.html`.
4. Confirme que o arquivo aparece em `git lfs ls-files` antes do push.

## Blog

Os cards de blog ja estao como temas sugeridos. Quando houver artigos reais, transforme cada card em link para a pagina ou plataforma onde o texto for publicado.

## Depoimentos

A secao esta pronta para usar Doctoralia e Google. Quando surgirem avaliacoes publicas, adicione apenas trechos autorizados e, de preferencia, com fonte.

## LGPD

O site inclui um aviso simples de privacidade. Antes da publicacao oficial, valide o texto de politica de privacidade com a medica ou com orientacao juridica, se necessario.

## Favicon

O favicon fica em:

```txt
site/favicon.svg
```

Ele ja esta na paleta vinho e dourado. Pode ser substituido por um arquivo da identidade visual oficial mantendo o mesmo nome.