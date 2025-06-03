# 📜 Comandos HTML5 e CSS3: Do Básico ao Avançado

Este documento lista **200 comandos, elementos, propriedades e conceitos do HTML5 e CSS3**, organizados por categoria e ordenados do básico ao avançado. Cada item inclui uma breve descrição e, quando aplicável, um exemplo. As categorias são:

1. **🔍 HTML5 Básico (Estrutura, Tags, Atributos)**
2. **🛠️ CSS3 Básico (Seletores, Propriedades de Estilo, Layouts)**
3. **🚀 Avançado (HTML5 Semântico, CSS3 Animações, Responsividade, APIs)**

---

## 1. 🔍 HTML5 Básico

Elementos e atributos fundamentais para estruturar páginas web.

### Estrutura e Metadados
1. **`<!DOCTYPE html>`** - Declara documento HTML5.  
   - Exemplo: `<!DOCTYPE html>`
2. **`<html>`** - Raiz do documento.  
   - Exemplo: `<html lang="en">`
3. **`<head>`** - Contém metadados.  
   - Exemplo: `<head>`
4. **`<meta>`** - Define metadados.  
   - Exemplo: `<meta charset="UTF-8">`
5. **`<title>`** - Define título da página.  
   - Exemplo: `<title>My Page</title>`
6. **`<link>`** - Conecta recursos externos (ex.: CSS).  
   - Exemplo: `<link rel="stylesheet" href="styles.css">`
7. **`<style>`** - Inclui CSS no documento.  
   - Exemplo: `<style> body { color: blue; } </style>`
8. **`<script>`** - Inclui JavaScript.  
   - Exemplo: `<script src="script.js"></script>`
9. **`<base>`** - Define URL base para links.  
   - Exemplo: `<base href="https://example.com/">`

### Elementos de Texto
10. **`<h1>`** to **`<h6>`** - Títulos de nível 1 a 6.  
    - Exemplo: `<h1>Main Heading</h1>`
11. **`<p>`** - Parágrafo.  
    - Exemplo: `<p>This is a paragraph.</p>`
12. **`<br>`** - Quebra de linha.  
    - Exemplo: `<br>`
13. **`<hr>`** - Linha horizontal.  
    - Exemplo: `<hr>`
14. **`<strong>`** - Texto em negrito.  
    - Exemplo: `<strong>Bold</strong>`
15. **`<em>`** - Texto em itálico.  
    - Exemplo: `<em>Italic</em>`
16. **`<span>`** - Contêiner inline genérico.  
    - Exemplo: `<span>Inline</span>`
17. **`<div>`** - Contêiner de bloco genérico.  
    - Exemplo: `<div>Block</div>`

### Listas
18. **`<ul>`** - Lista não ordenada.  
    - Exemplo: `<ul><li>Item</li></ul>`
19. **`<ol>`** - Lista ordenada.  
    - Exemplo: `<ol><li>Item</li></ol>`
20. **`<li>`** - Item de lista.  
    - Exemplo: `<li>Item</li>`
21. **`<dl>`** - Lista de descrição.  
    - Exemplo: `<dl><dt>Term</dt><dd>Definition</dd></dl>`
22. **`<dt>`** - Termo em lista de descrição.  
    - Exemplo: `<dt>Term</dt>`
23. **`<dd>`** - Descrição em lista de descrição.  
    - Exemplo: `<dd>Definition</dd>`

### Links e Imagens
24. **`<a>`** - Link hipertexto.  
    - Exemplo: `<a href="https://example.com">Link</a>`
25. **`<img>`** - Insere imagem.  
    - Exemplo: `<img src="image.jpg" alt="Description">`
26. **`<figure>`** - Agrupa mídia com legenda.  
    - Exemplo: `<figure><img src="img.jpg"><figcaption>Caption</figcaption></figure>`
27. **`<figcaption>`** - Legenda para figure.  
    - Exemplo: `<figcaption>Caption</figcaption>`

### Formulários
28. **`<form>`** - Define formulário.  
    - Exemplo: `<form action="/submit" method="post">`
29. **`<input>`** - Campo de entrada.  
    - Exemplo: `<input type="text" name="username">`
30. **`<textarea>`** - Área de texto.  
    - Exemplo: `<textarea name="comment"></textarea>`
31. **`<button>`** - Botão clicável.  
    - Exemplo: `<button type="submit">Submit</button>`
32. **`<select>`** - Lista suspensa.  
    - Exemplo: `<select name="options"><option>Option</option></select>`
33. **`<option>`** - Item de select.  
    - Exemplo: `<option value="value">Option</option>`
34. **`<label>`** - Rótulo para input.  
    - Exemplo: `<label for="id">Label</label>`
35. **`<fieldset>`** - Agrupa controles de formulário.  
    - Exemplo: `<fieldset><legend>Group</legend></fieldset>`
36. **`<legend>`** - Título do fieldset.  
    - Exemplo: `<legend>Group</legend>`

### Atributos
37. **`id`** - Identificador único.  
    - Exemplo: `<div id="unique">`
38. **`class`** - Classe para estilização.  
    - Exemplo: `<div class="container">`
39. **`style`** - Estilo inline.  
    - Exemplo: `<div style="color: blue;">`
40. **`href`** - URL do link.  
    - Exemplo: `<a href="https://example.com">`
41. **`src`** - Fonte do recurso.  
    - Exemplo: `<img src="image.jpg">`
42. **`alt`** - Texto alternativo.  
    - Exemplo: `<img alt="Description">`
43. **`type`** - Tipo de input ou botão.  
    - Exemplo: `<input type="email">`
44. **`name`** - Nome do campo de formulário.  
    - Exemplo: `<input name="username">`
45. **`value`** - Valor do campo.  
    - Exemplo: `<input value="default">`
46. **`placeholder`** - Texto de dica.  
    - Exemplo: `<input placeholder="Enter text">`
47. **`required`** - Campo obrigatório.  
    - Exemplo: `<input required>`
48. **`disabled`** - Desativa elemento.  
    - Exemplo: `<input disabled>`
49. **`data-*`** - Atributos personalizados.  
    - Exemplo: `<div data-info="custom">`
50. **`lang`** - Define idioma.  
    - Exemplo: `<html lang="en">`

---

## 2. 🛠️ CSS3 Básico

Propriedades e seletores para estilizar e organizar layouts.

### Seletores
51. **`element`** - Seleciona elemento HTML.  
    - Exemplo: `p { color: blue; }`
52. **`.class`** - Seleciona por classe.  
    - Exemplo: `.container { margin: 0; }`
53. **`#id`** - Seleciona por ID.  
    - Exemplo: `#header { background: gray; }`
54. **`[attribute]`** - Seleciona por atributo.  
    - Exemplo: `[type="text"] { border: 1px solid; }`
55. **`:hover`** - Estiliza ao passar o mouse.  
    - Exemplo: `button:hover { background: blue; }`
56. **`:active`** - Estiliza ao clicar.  
    - Exemplo: `button:active { color: red; }`
57. **`:focus`** - Estiliza ao focar.  
    - Exemplo: `input:focus { outline: none; }`
58. **`::before`** - Insere conteúdo antes do elemento.  
    - Exemplo: `p::before { content: "*"; }`
59. **`::after`** - Insere conteúdo após o elemento.  
    - Exemplo: `p::after { content: "."; }`
60. **`>`** - Seleciona filho direto.  
    - Exemplo: `ul > li { margin: 5px; }`
61. **`+`** - Seleciona irmão adjacente.  
    - Exemplo: `h1 + p { margin-top: 10px; }`
62. **`~`** - Seleciona irmãos subsequentes.  
    - Exemplo: `h1 ~ p { color: gray; }`

### Propriedades de Texto
63. **`color`** - Define cor do texto.  
    - Exemplo: `color: #333;`
64. **`font-size`** - Define tamanho da fonte.  
    - Exemplo: `font-size: 16px;`
65. **`font-family`** - Define família da fonte.  
    - Exemplo: `font-family: Arial, sans-serif;`
66. **`font-weight`** - Define espessura da fonte.  
    - Exemplo: `font-weight: bold;`
67. **`text-align`** - Alinha texto.  
    - Exemplo: `text-align: center;`
68. **`text-decoration`** - Adiciona decoração (ex.: sublinhado).  
    - Exemplo: `text-decoration: underline;`
69. **`line-height`** - Define altura da linha.  
    - Exemplo: `line-height: 1.5;`
70. **`letter-spacing`** - Define espaçamento entre letras.  
    - Exemplo: `letter-spacing: 2px;`
71. **`text-transform`** - Transforma texto (ex.: maiúsculas).  
    - Exemplo: `text-transform: uppercase;`

### Propriedades de Caixa
72. **`width`** - Define largura.  
    - Exemplo: `width: 100px;`
73. **`height`** - Define altura.  
    - Exemplo: `height: 100px;`
74. **`margin`** - Define margem externa.  
    - Exemplo: `margin: 10px;`
75. **`padding`** - Define margem interna.  
    - Exemplo: `padding: 10px;`
76. **`border`** - Define borda.  
    - Exemplo: `border: 1px solid black;`
77. **`border-radius`** - Arredonda cantos.  
    - Exemplo: `border-radius: 5px;`
78. **`box-shadow`** - Adiciona sombra.  
    - Exemplo: `box-shadow: 2px 2px 5px rgba(0,0,0,0.3);`
79. **`background-color`** - Define cor de fundo.  
    - Exemplo: `background-color: #f0f0f0;`
80. **`background-image`** - Define imagem de fundo.  
    - Exemplo: `background-image: url("bg.jpg");`
81. **`background-size`** - Define tamanho da imagem de fundo.  
    - Exemplo: `background-size: cover;`
82. **`background-position`** - Define posição do fundo.  
    - Exemplo: `background-position: center;`
83. **`background-repeat`** - Controla repetição do fundo.  
    - Exemplo: `background-repeat: no-repeat;`

### Posicionamento
84. **`position`** - Define tipo de posicionamento.  
    - Exemplo: `position: relative;`
85. **`top`** - Posiciona do topo.  
    - Exemplo: `top: 10px;`
86. **`right`** - Posiciona da direita.  
    - Exemplo: `right: 10px;`
87. **`bottom`** - Posiciona da base.  
    - Exemplo: `bottom: 10px;`
88. **`left`** - Posiciona da esquerda.  
    - Exemplo: `left: 10px;`
89. **`z-index`** - Define ordem de empilhamento.  
    - Exemplo: `z-index: 10;`
90. **`display`** - Define comportamento de exibição.  
    - Exemplo: `display: block;`
91. **`float`** - Flutua elemento.  
    - Exemplo: `float: left;`
92. **`clear`** - Limpa flutuação.  
    - Exemplo: `clear: both;`

### Layouts
93. **`box-sizing`** - Define modelo de caixa.  
    - Exemplo: `box-sizing: border-box;`
94. **`overflow`** - Controla conteúdo excedente.  
    - Exemplo: `overflow: auto;`
95. **`visibility`** - Controla visibilidade.  
    - Exemplo: `visibility: hidden;`
96. **`opacity`** - Define transparência.  
    - Exemplo: `opacity: 0.5;`
97. **`cursor`** - Define tipo de cursor.  
    - Exemplo: `cursor: pointer;`
98. **`text-overflow`** - Controla texto excedente.  
    - Exemplo: `text-overflow: ellipsis;`
99. **`white-space`** - Controla espaçamento de texto.  
    - Exemplo: `white-space: nowrap;`
100. **`vertical-align`** - Alinha verticalmente.  
     - Exemplo: `vertical-align: middle;`

---

## 3. 🚀 Avançado

Elementos semânticos do HTML5, recursos avançados do CSS3 e APIs modernas.

### HTML5 Semântico
101. **`<header>`** - Cabeçalho da página ou seção.  
     - Exemplo: `<header><h1>Title</h1></header>`
102. **`<nav>`** - Navegação principal.  
     - Exemplo: `<nav><a href="#">Link</a></nav>`
103. **`<main>`** - Conteúdo principal.  
     - Exemplo: `<main><p>Content</p></main>`
104. **`<article>`** - Conteúdo independente.  
     - Exemplo: `<article><h2>Post</h2></article>`
105. **`<section>`** - Seção temática.  
     - Exemplo: `<section><h2>Topic</h2></section>`
106. **`<aside>`** - Conteúdo lateral.  
     - Exemplo: `<aside><p>Sidebar</p></aside>`
107. **`<footer>`** - Rodapé da página ou seção.  
     - Exemplo: `<footer><p>Copyright</p></footer>`
108. **`<details>`** - Conteúdo expansível.  
     - Exemplo: `<details><summary>More</summary><p>Info</p></details>`
109. **`<summary>`** - Título de details.  
     - Exemplo: `<summary>More</summary>`
110. **`<mark>`** - Destaca texto.  
     - Exemplo: `<mark>Highlighted</mark>`
111. **`<time>`** - Representa data/hora.  
     - Exemplo: `<time datetime="2023-01-01">Jan 1</time>`
112. **`<progress>`** - Barra de progresso.  
     - Exemplo: `<progress value="50" max="100"></progress>`
113. **`<meter>`** - Medidor de valor.  
     - Exemplo: `<meter value="75" min="0" max="100"></meter>`

### Multimídia
114. **`<video>`** - Insere vídeo.  
     - Exemplo: `<video src="video.mp4" controls></video>`
115. **`<audio>`** - Insere áudio.  
     - Exemplo: `<audio src="audio.mp3" controls></audio>`
116. **`<source>`** - Define fonte para vídeo/áudio.  
     - Exemplo: `<source src="video.mp4" type="video/mp4">`
117. **`<track>`** - Adiciona legendas.  
     - Exemplo: `<track src="subtitles.vtt" kind="subtitles">`
118. **`<canvas>`** - Desenha gráficos via JavaScript.  
     - Exemplo: `<canvas id="myCanvas"></canvas>`
119. **`<svg>`** - Define gráficos vetoriais.  
     - Exemplo: `<svg><circle cx="50" cy="50" r="40"/></svg>`

### Formulários Avançados
120. **`type="email"`** - Input para e-mail.  
     - Exemplo: `<input type="email">`
121. **`type="url"`** - Input para URL.  
     - Exemplo: `<input type="url">`
122. **`type="tel"`** - Input para telefone.  
     - Exemplo: `<input type="tel">`
123. **`type="number"`** - Input numérico.  
     - Exemplo: `<input type="number">`
124. **`type="range"`** - Input de intervalo.  
     - Exemplo: `<input type="range" min="0" max="100">`
125. **`type="date"`** - Input de data.  
     - Exemplo: `<input type="date">`
126. **`pattern`** - Valida entrada com regex.  
     - Exemplo: `<input pattern="[A-Za-z]{3}">`
127. **`autocomplete`** - Controla autocompletar.  
     - Exemplo: `<input autocomplete="on">`
128. **`autofocus`** - Foca automaticamente.  
     - Exemplo: `<input autofocus>`
129. **`multiple`** - Permite múltiplos valores.  
     - Exemplo: `<input type="file" multiple>`

### CSS3 Flexbox
130. **`display: flex`** - Ativa layout flexível.  
     - Exemplo: `display: flex;`
131. **`flex-direction`** - Define direção dos itens.  
     - Exemplo: `flex-direction: row;`
132. **`flex-wrap`** - Controla quebra de linha.  
     - Exemplo: `flex-wrap: wrap;`
133. **`justify-content`** - Alinha itens no eixo principal.  
     - Exemplo: `justify-content: center;`
134. **`align-items`** - Alinha itens no eixo cruzado.  
     - Exemplo: `align-items: center;`
135. **`align-content`** - Alinha linhas no eixo cruzado.  
     - Exemplo: `align-content: space-between;`
136. **`flex-grow`** - Define crescimento do item.  
     - Exemplo: `flex-grow: 1;`
137. **`flex-shrink`** - Define encolhimento do item.  
     - Exemplo: `flex-shrink: 0;`
138. **`flex-basis`** - Define tamanho base do item.  
     - Exemplo: `flex-basis: 200px;`
139. **`flex`** - Atalho para grow/shrink/basis.  
     - Exemplo: `flex: 1 1 auto;`

### CSS3 Grid
140. **`display: grid`** - Ativa layout de grade.  
     - Exemplo: `display: grid;`
141. **`grid-template-columns`** - Define colunas.  
     - Exemplo: `grid-template-columns: 1fr 1fr;`
142. **`grid-template-rows`** - Define linhas.  
     - Exemplo: `grid-template-rows: 100px auto;`
143. **`grid-gap`** - Define espaçamento entre células.  
     - Exemplo: `grid-gap: 10px;`
144. **`grid-column`** - Define posição/extensão da coluna.  
     - Exemplo: `grid-column: 1 / 3;`
145. **`grid-row`** - Define posição/extensão da linha.  
     - Exemplo: `grid-row: 1 / 2;`
146. **`justify-items`** - Alinha itens na grade.  
     - Exemplo: `justify-items: center;`
147. **`align-items`** - Alinha itens verticalmente na grade.  
     - Exemplo: `align-items: center;`

### CSS3 Animações e Transições
148. **`transition`** - Define transições suaves.  
     - Exemplo: `transition: all 0.3s ease;`
149. **`transition-property`** - Propriedade a transicionar.  
     - Exemplo: `transition-property: opacity;`
150. **`transition-duration`** - Duração da transição.  
     - Exemplo: `transition-duration: 0.5s;`
151. **`transition-timing-function`** - Curva de transição.  
     - Exemplo: `transition-timing-function: ease-in;`
152. **`animation`** - Define animação.  
     - Exemplo: `animation: slide 2s infinite;`
153. **`@keyframes`** - Define quadros da animação.  
     - Exemplo: `@keyframes slide { from { left: 0; } to { left: 100px; } }`
154. **`animation-name`** - Nome da animação.  
     - Exemplo: `animation-name: slide;`
155. **`animation-duration`** - Duração da animação.  
     - Exemplo: `animation-duration: 2s;`
156. **`animation-iteration-count`** - Número de repetições.  
     - Exemplo: `animation-iteration-count: infinite;`
157. **`animation-delay`** - Atraso inicial.  
     - Exemplo: `animation-delay: 1s;`
158. **`transform`** - Aplica transformações (ex.: rotação).  
     - Exemplo: `transform: rotate(45deg);`
159. **`translate()`** - Move elemento.  
     - Exemplo: `transform: translate(50px, 50px);`
160. **`scale()`** - Redimensiona elemento.  
     - Exemplo: `transform: scale(1.5);`
161. **`rotate()`** - Rotaciona elemento.  
     - Exemplo: `transform: rotate(90deg);`

### Responsividade
162. **`@media`** - Define regras para diferentes dispositivos.  
     - Exemplo: `@media (max-width: 600px) { body { font-size: 14px; } }`
163. **`vw`** - Unidade de viewport width.  
     - Exemplo: `width: 50vw;`
164. **`vh`** - Unidade de viewport height.  
     - Exemplo: `height: 50vh;`
165. **`rem`** - Unidade relativa ao root font-size.  
     - Exemplo: `font-size: 2rem;`
166. **`em`** - Unidade relativa ao font-size do elemento.  
     - Exemplo: `padding: 1em;`
167. **`%`** - Unidade percentual.  
     - Exemplo: `width: 50%;`
168. **`min-width`** - Largura mínima.  
     - Exemplo: `min-width: 300px;`
169. **`max-width`** - Largura máxima.  
     - Exemplo: `max-width: 1200px;`
170. **`viewport meta`** - Controla zoom em dispositivos móveis.  
     - Exemplo: `<meta name="viewport" content="width=device-width, initial-scale=1">`

### CSS3 Avançado
171. **`filter`** - Aplica efeitos visuais (ex.: blur).  
     - Exemplo: `filter: blur(5px);`
172. **`clip-path`** - Define área de recorte.  
     - Exemplo: `clip-path: polygon(0 0, 100% 0, 100% 100%);`
173. **`object-fit`** - Controla ajuste de imagens/vídeos.  
     - Exemplo: `object-fit: cover;`
174. **`backdrop-filter`** - Aplica filtro ao fundo.  
     - Exemplo: `backdrop-filter: blur(10px);`
175. **`var()`** - Usa variável CSS.  
     - Exemplo: `color: var(--main-color);`
176. **`--variable`** - Define variável CSS.  
     - Exemplo: `:root { --main-color: blue; }`
177. **`calc()`** - Realiza cálculos.  
     - Exemplo: `width: calc(100% - 20px);`
178. **`gradient`** - Define gradiente.  
     - Exemplo: `background: linear-gradient(to right, red, blue);`
179. **`linear-gradient()`** - Gradiente linear.  
     - Exemplo: `background: linear-gradient(red, blue);`
180. **`radial-gradient()`** - Gradiente radial.  
     - Exemplo: `background: radial-gradient(circle, red, blue);`

### HTML5 APIs
181. **`Geolocation API`** - Obtém localização do usuário.  
     - Exemplo: `navigator.geolocation.getCurrentPosition(callback)`
182. **`Canvas API`** - Desenha gráficos 2D.  
     - Exemplo: `ctx.fillRect(0, 0, 100, 100)`
183. **`Web Storage`** - Armazena dados localmente.  
     - Exemplo: `localStorage.setItem("key", "value")`
184. **`localStorage`** - Armazenamento persistente.  
     - Exemplo: `localStorage.getItem("key")`
185. **`sessionStorage`** - Armazenamento por sessão.  
     - Exemplo: `sessionStorage.setItem("key", "value")`
186. **`Drag and Drop API`** - Suporta arrastar e soltar.  
     - Exemplo: `<div draggable="true" ondragstart="event.dataTransfer.setData()">`
187. **`Web Workers`** - Executa scripts em segundo plano.  
     - Exemplo: `const worker = new Worker("worker.js")`
188. **`WebSockets`** - Comunicação bidirecional.  
     - Exemplo: `const socket = new WebSocket("ws://example.com")`

### Acessibilidade
189. **`aria-label`** - Define rótulo acessível.  
     - Exemplo: `<button aria-label="Close">X</button>`
190. **`aria-hidden`** - Oculta elemento de leitores de tela.  
     - Exemplo: `<div aria-hidden="true">`
191. **`role`** - Define papel semântico.  
     - Exemplo: `<div role="button">`
192. **`tabindex`** - Controla ordem de navegação.  
     - Exemplo: `<div tabindex="0">`

### Outros
193. **`contenteditable`** - Torna elemento editável.  
     - Exemplo: `<div contenteditable="true">`
194. **`spellcheck`** - Ativa verificação ortográfica.  
     - Exemplo: `<textarea spellcheck="true">`
195. **`hidden`** - Oculta elemento.  
     - Exemplo: `<div hidden>`
196. **`download`** - Força download de arquivo.  
     - Exemplo: `<a href="file.pdf" download>`
197. **`media query`** - Adapta estilos por dispositivo.  
     - Exemplo: `@media (min-width: 768px) { }`
198. **`:root`** - Seleciona elemento raiz.  
     - Exemplo: `:root { --color: blue; }`
199. **`!important`** - Aumenta prioridade de regra.  
     - Exemplo: `color: blue !important;`
200. **`currentColor`** - Usa cor atual.  
     - Exemplo: `border-color: currentColor;`

---

## 📝 Notas Finais
- **Compatibilidade**: Alguns recursos (ex.: `backdrop-filter`) podem não ser suportados em navegadores antigos.
- **Boas Práticas**: Use HTML semântico, prefira Flexbox/Grid para layouts, e inclua ARIA para acessibilidade.
- **Exploração**: Consulte a documentação da MDN (developer.mozilla.org) para detalhes.