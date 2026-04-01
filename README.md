# Opus Família & Legado — Landing Page

Site institucional da **Opus Família & Legado**, plataforma white-label de wealth planning B2B.

## Estrutura do projeto

```
opus-site/
├── index.html        # Página principal (HTML + CSS + JS inline)
├── images/
│   ├── founder.jpeg  # Foto da fundadora Marina Gonçalves
│   └── building.svg  # Imagem de background (arquitetura)
├── netlify.toml      # Configuração de deploy e cache headers
├── .gitignore
└── README.md
```

## Deploy

O site é hospedado via **Netlify** com deploy automático a partir da branch `main`.

Para fazer deploy manualmente:
1. Faça push para a branch `main`
2. O Netlify detecta automaticamente e publica

## Desenvolvimento local

Basta abrir `index.html` no navegador — não há dependências de build.

```bash
# Opcional: servidor local simples com Python
python3 -m http.server 8080
# Acesse: http://localhost:8080
```

## Customização

Todas as variáveis de cor e tipografia estão no bloco `:root` no início do `<style>` em `index.html`:

```css
:root {
  --navy: #2C3E50;
  --gold: #D4A574;
  --serif: 'Playfair Display', Georgia, serif;
  --sans: 'DM Sans', system-ui, sans-serif;
}
```

## Contato

- Instagram: [@opusfl.consultoria](https://www.instagram.com/opusfl.consultoria)
- LinkedIn: [Opus Família & Legado](https://www.linkedin.com/company/opus-fam%C3%ADlia-legado/)
