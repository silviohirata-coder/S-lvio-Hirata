# Sílvio Hirata — Portfólio

Site de portfólio pessoal, estático (HTML/CSS/JS puros, sem dependências ou build).

## Estrutura

```
index.html      # conteúdo e estrutura da página
css/style.css   # estilos
js/main.js      # menu mobile, ano no rodapé e envio do formulário de contato
```

## Como visualizar

Basta abrir `index.html` diretamente no navegador, ou servir a pasta com qualquer
servidor estático, por exemplo:

```
python3 -m http.server 8000
```

e acessar `http://localhost:8000`.

## Personalizando

O conteúdo atual usa textos de exemplo (placeholder). Edite `index.html` para:

- Trocar o cargo/subtítulo em `.hero-subtitle` e a descrição em `.hero-description`
- Preencher a seção "Sobre mim" com seu texto real
- Atualizar as habilidades na seção `#skills`
- Substituir os projetos de exemplo na seção `#projects` (título, descrição e link)
- Atualizar os links de redes sociais e e-mail na seção `#contact`

O formulário de contato é apenas visual — para receber mensagens de verdade, conecte-o
a um serviço como Formspree, Netlify Forms, ou a um backend próprio.

## Publicando

Este site pode ser hospedado gratuitamente em serviços como GitHub Pages, Netlify ou
Vercel, já que não depende de nenhum processo de build.
