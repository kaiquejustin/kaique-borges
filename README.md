<div id="acessibilidade" class="menu-acessibilidade">
    <button id="botao-acessibilidade" class="btn btn-primary fw-bold rotacao-botao" aria-expanded="false">acessibilidade</button>
</div>const botaoSelecionado = botaoDeAcessibilidade.getAttribute('aria-expanded') === 'true';
const botaoSelecionado = botaoDeAcessibilidade.getAttribute('aria-expanded') === 'true';
botaoDeAcessibilidade.setAttribute('aria-expanded', !botaoSelecionado)
<section id="tropicalia" class="my-5 pt-6 secao-tropicalia" tabindex="0" aria-label="Seção explicativa sobre a Tropicália">
<section id="galeria" tabindex="0" aria-label="Seção de galeria de imagens">
https://cdnjs.cloudflare.com/ajax/libs/scrollReveal.js/4.0.9/scrollreveal.js
<script src="https://cdnjs.cloudflare.com/ajax/libs/scrollReveal.js/4.0.9/scrollreveal.js"></script>
ScrollReveal().reveal('#inicio', { delay: 500 });
ScrollReveal().reveal('#inicio', { delay: 500 });
ScrollReveal().reveal('#tropicalia', { delay: 500 });
ScrollReveal().reveal('#galeria', { delay: 500 });
ScrollReveal().reveal('#contato', { delay: 500 });
# Site acessível sobre Tropicália
## Sobre
Refatoração de um site implementando recursos de acessibilidade no HTML, CSS e JS.
## Recursos de acessibilidade
- Atributos aria
- Alt
- Tab-index
- Menu de acessibilidade
## Tecnologias utilizadas
- Bootstrap
- ScrollReveal.js
- HTML
- CSS
- JS
