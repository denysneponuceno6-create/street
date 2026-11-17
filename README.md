# Street — Landing Page de Apresentação

Landing page moderna e interativa para apresentação do catálogo de sneakers **Street**.

## Características

- Design dark com identidade visual laranja (logo Street)
- Catálogo interativo com filtros por categoria
- Busca em tempo real
- Modal de detalhes do produto
- Preços atualizados (desconto de R$ 150 em relação à versão anterior)
- Totalmente responsivo (mobile-first)
- Performance otimizada (sem build, Tailwind CDN)
- Contato via Instagram e WhatsApp

## Contato

- Instagram: [@loja_street2k25](https://instagram.com/loja_street2k25)
- WhatsApp: (11) 95856-6772

## Como usar

Basta abrir o arquivo `index.html` no navegador.

```bash
# Ou servir localmente
npx serve .
# ou
python3 -m http.server 8080
```

## Estrutura

```
street-landing/
├── index.html              # Página principal
├── public/images/
│   └── logo-street.jpg     # Logo Street
└── README.md
```

## Deploy

Pode ser publicado em qualquer hospedagem estática:
- Vercel / Netlify / Cloudflare Pages
- GitHub Pages
- Qualquer servidor web

## Notas

- Imagens dos produtos carregadas diretamente do CDN
- Site de apresentação — sem carrinho/checkout
