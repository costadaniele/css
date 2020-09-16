# CSS - Conteúdo do Curso de Extensão CSS: folhas de estilo

- Instituto Federal de Educação, Ciência e Tecnologia do Rio Grande do Sul

---

- Folha de estilos.
- Estilos podem ser atribuídos:
   - A uma tag HTML;
   - A uma classe (class): conjunto de elementos com as mesmas propriedades; 
      - .class
   - A um ID (identifcador): elemento único. 
      - #id

 - id's e classes ficam dentro de tags
    - as tags podem receber id's e classes juntas ou separadas.
    - no css as os id's e as classes podem ser declaradas referenciando uma tag específica.
        
        Exemplo:
        
         `p #nomeid {`
            `font-size: 12px;`  
            `}`

        ou

        referenciando todas as tags que tem essa classe

        `#nomeclass {`
            `font-size: 12px;`        
            `}`

- Css pode ser interno (dentro do HTML) ou externo (fora do HTML), vinculando a página CSS.

- Alinhamento do texto:

`text-align: center;`
`text-align: left;`
`text-align: right;`
`text-align: justify;`

---

- Espaçamento do texto:

`letter-spacing: 0.5em;`

---

- Espaçamento de palavras:

`word-spacing: 0.5em;`

---

- Unidades de tamanho:

   - Relativo

    - %  - img
    - em
    - ex
    - px - img

   - Absoluto
    
    - in
    - cm
    - mm
    - pt - fontes
    - pc

---

- Decoração do texto:

`text-decoration: underline;`
`text-decoration: overline;`
`text-decoration: line-through;`

--- 

- Recuo do texto:

`text-indent: 30pt;`

--- 

- Sombra:

`text-shadow: blue 5px 6px 2px;`

cor / deslocamento a direita / deslocamento para baixo / esfumaçado

--- 

- Letras maiúsculas

`text-transform: capitalize;`

--- 

Sem quebra de linha: 

`white-space: nowrap;`

---

Itálico

`font-style: italic;`

--- 

- Links 


`a:link {`
    `color: #044b7f;`
`}`

quando o link for visitado

`a:visited {`
    `color: green;`
`}`

quando passa o mouse

`a:hover {`
    `color: #95190c;`
`}`

link ativo - ao clicar 

`a:active {`
    `color:#610345;`
`}`

- Listas com imagens

Na tag <ul>

lista com imagem

`list-style-image: url(doces.jpg);`

posição da imagem

`list-style-position: inside;`

- Lista com marcadores

ordem alfabética com letras minúsculas
`list-style-type: lower-alpha;`
ordem alfabética com letras maiúsculas
`list-style-type: upper-alpha;`

`list-style-type: disc;`
`list-style-type: circle;`
`list-style-type: square;`

números que começam com zero
`list-style-type: decimal-leading-zero;`

números romanos minúsculo
`list-style-type: lower-roman;`

números romanos maiúsculo
`list-style-type: upper-roman;`

`list-style-type: hiragana;`
`list-style-type: katakana;`
`list-style-type: katakana-iroha;`
`list-style-type: hiragana-iroha;`

`list-style-type: armenian;`
`list-style-type: georgian;`
`list-style-type: hebrew;`

`list-style-type: lower-greek;`
`list-style-type: lower-latin;`
`list-style-type: upper-latin;`

- Menus pronto CSS

http://cssmenumaker.com/free-css-menus

## Media Query

- Responsividade

## Div

- Posicionamento

---
propriedade: valor;

`border-style: solid;`
`border-style: dotted;`

`border-width: 2px;`

posição fixa
`position: absolute;`

Referência:

https://www.w3schools.com/css/css_boxmodel.asp

http://learnlayout.com/inline-block.html

https://www.w3schools.com/css/css_positioning.asp

https://templated.co/