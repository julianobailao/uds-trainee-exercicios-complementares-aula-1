

HTML é uma linguagem de Marcação de Hypertexto

CSS é uma linguagem de formatação de estilos

Cite 3 tags HTML, e descreva suas funções.
  <br> abreviação da palavra break, serve para determinar uma quebra de linha.
  <p> </p> Utilizado para criação de parágrafos.
  <h1...h6> </h1.../h6> Criação de Titulos e sub-Titulos

Aplique CSS no HTML a seguir <a href="http://google.com">Ir para o google</a>, de modo que:

    A fonte seja arial, tamanho 32px, negrito
    A cor do texto seja branca
    A cor do fundo seja azul
    O espaçamento interno seja 10px
    Ao passar o mouse, a cor de fundo seja vermelho, com uma trasição sutil entre as cores

RESPOSTA:

<html language="pt-br">
  <head>
     <meta charset="UTF-8">
     <style>
        .links{
          background: blue;
          width: 225px;
          -webkit-transition: 0.5s ease-out;
          -moz-transition: 0.5s ease-out;
          -o-transition: 0.5s ease-out;
          transition: 0.5s ease-out;
          font-size: 32px;
          font-family: Arial;
          padding-left: 10px;
          padding-right: 10px;
        }
        .links:hover{
          background: red;
        }
        .links a {
            color: white;
        }
     </style>
  </head>
  <body>
    <div class="links">
      <a href="http://google.com"> Ir para o google</a>
    </div>
  </body>
</HTML>
