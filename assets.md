# Assets – JR Atacadista

## Estrutura de pastas

```
JR Atacadista/
├── index.html
├── public/
│   ├── images/       ← imagens gerais (banners, fotos de produtos, fundos)
│   ├── icons/        ← ícones SVG / favicon
│   └── fonts/        ← fontes customizadas (.woff2, .ttf)
└── assets.md         ← este arquivo
```

## Imagens a adicionar

| Arquivo                     | Uso                          | Tamanho sugerido |
|-----------------------------|------------------------------|-----------------|
| logo.png / logo.svg         | Logo principal               | 300×100px       |
| logo-branco.png             | Logo versão branca (footer)  | 300×100px       |
| favicon.ico / favicon.png   | Aba do navegador             | 32×32px         |
| hero-banner.jpg             | Banner principal (hero)      | 1920×1080px     |
| og-image.jpg                | Preview em redes sociais     | 1200×630px      |

## Como usar no HTML

```html
<!-- Logo -->
<img src="public/images/logo.png" alt="JR Atacadista">

<!-- Favicon -->
<link rel="icon" href="public/icons/favicon.ico">

<!-- Fonte local -->
<style>
  @font-face {
    font-family: 'MinhaFonte';
    src: url('public/fonts/minha-fonte.woff2') format('woff2');
  }
</style>
```
