# Desenvolvimento Front-End para Web

**Aluno:** Guilherme Araújo Targino  
**RGM:** 48753785  
**Curso:** Ciência da Computação

Repositório dedicado à organização dos conteúdos, códigos, exercícios e atividades práticas desenvolvidos durante a disciplina de Desenvolvimento Front-End para Web.

## Índice

- [Aula 02 — Títulos, listas e tabelas](#aula-02--títulos-listas-e-tabelas)
- [Aula 03 — Imagens, tabelas e primeiros estilos](#aula-03--imagens-tabelas-e-primeiros-estilos)
- [Aula 04 — Links e HTML semântico](#aula-04--links-e-html-semântico)
- [Aula 05 — Áudio, vídeo e formulários](#aula-05--áudio-vídeo-e-formulários)
- [Aula 06 — CSS externo](#aula-06--css-externo)
- [Aula 07 — Classes e IDs](#aula-07--classes-e-ids)
- [Aula 08 — Layout de páginas web](#aula-08--layout-de-páginas-web)
- [Aula 09 — JavaScript e eventos](#aula-09--javascript-e-eventos)
- [Aula 10 — Estruturas de repetição e funções](#aula-10--estruturas-de-repetição-e-funções)
- [Aula 11 — Bootstrap 5 e Cards](#aula-11--bootstrap-5-e-cards)

---

## Aula 02 — Títulos, listas e tabelas

Introdução à estruturação de conteúdo utilizando HTML.

**Conteúdos:** estrutura básica do HTML, títulos, subtítulos, parágrafos, listas ordenadas e não ordenadas e tabelas.

**Principais tags:**

| Tag | Função |
|---|---|
| `h1` até `h6` | Títulos e subtítulos |
| `p` | Parágrafos |
| `ul` e `ol` | Listas |
| `li` | Item de lista |
| `table` | Tabela |
| `tr`, `th` e `td` | Linhas, cabeçalhos e células |

## Aula 03 — Imagens, tabelas e primeiros estilos

Aprofundamento em HTML, organização de tabelas, inserção de imagens e introdução à estilização.

**Conteúdos:** `thead`, `tbody`, imagens, `figure`, `figcaption`, introdução ao CSS e primeiros contatos com JavaScript.

```html
<table>
  <thead>
    <tr><th>Nome</th><th>Idade</th></tr>
  </thead>
  <tbody>
    <tr><td>Guilherme</td><td>19</td></tr>
  </tbody>
</table>

<figure>
  <img src="imagem.jpg" alt="Descrição da imagem">
  <figcaption>Legenda da imagem</figcaption>
</figure>
```

## Aula 04 — Links e HTML semântico

Criação de links para navegação entre páginas e utilização de elementos semânticos.

**Conteúdos:** links internos e externos, caminhos relativos, navegação, imagens e organização semântica.

| Tag | Função |
|---|---|
| `a` | Links |
| `header` | Cabeçalho |
| `nav` | Navegação |
| `section` | Seção |
| `article` | Conteúdo independente |
| `footer` | Rodapé |
| `div` | Agrupamento |
| `br` e `hr` | Quebra de linha e separador |

```html
<a href="pagina.html">Acessar página</a>
```

## Aula 05 — Áudio, vídeo e formulários

Desenvolvimento de páginas com recursos multimídia e campos para entrada de informações.

**Conteúdos:** incorporação de áudio e vídeo, formulários, campos de entrada, botões e identificação com `label`.

```html
<audio controls>
  <source src="musica.mp3" type="audio/mpeg">
</audio>

<video controls width="400">
  <source src="video.mp4" type="video/mp4">
</video>

<form>
  <label for="nome">Nome:</label>
  <input type="text" id="nome" required>
  <label for="email">E-mail:</label>
  <input type="email" id="email" required>
  <button type="submit">Enviar</button>
</form>
```

## Aula 06 — CSS externo

Introdução à estilização de páginas HTML utilizando arquivos CSS externos.

**Conteúdos:** integração HTML e CSS, seletores, classes, cores, tipografia, margens, espaçamentos, bordas e alinhamento.

```html
<link rel="stylesheet" href="estilo.css">
```

```css
.titulo {
  color: blue;
  text-align: center;
}

.caixa01 {
  background-color: lightblue;
  border: 2px solid black;
  padding: 20px;
  margin: 10px;
}
```

**Principais propriedades:** `color`, `background-color`, `font-family`, `font-size`, `text-align`, `border`, `padding` e `margin`.

## Aula 07 — Classes e IDs

Identificação e estilização de elementos HTML utilizando classes e identificadores.

**Classes:** podem ser reutilizadas em vários elementos e são identificadas pelo ponto (`.`).

```html
<p class="destaque">Texto destacado.</p>
```

```css
.destaque {
  color: red;
  font-weight: bold;
}
```

**IDs:** identificam elementos específicos e são selecionados pelo símbolo `#`.

```html
<h1 id="titulo">Minha página</h1>
```

```css
#titulo {
  color: blue;
  text-align: center;
}
```

Também foram trabalhadas a organização dos arquivos HTML e CSS e a utilização de folhas de estilo externas, como `style01.css`.

## Aula 08 — Layout de páginas web

Desenvolvimento de interfaces e organização de elementos utilizando HTML e CSS.

**Conteúdos:** estruturação de layouts, distribuição de conteúdo, separação de áreas, elementos semânticos e estilização de componentes.

**Elementos utilizados:** `header`, `nav`, `main`, `section`, `article`, `aside` e `footer`.

**Atividade prática:** desenvolvimento de um layout de Portal Front-End, trabalhando a distribuição dos elementos e a organização visual da interface.

## Aula 09 — JavaScript e eventos

Introdução ao JavaScript e integração com HTML e CSS para adicionar funcionalidades às páginas.

**JavaScript incorporado:**

```html
<script>
  alert("JavaScript executado!");
</script>
```

**JavaScript externo:**

```html
<script src="script2.js" defer></script>
```

**Variáveis:**

```javascript
const nome = "Guilherme";
let resultado = 0;
```

- `const`: variável sem possibilidade de reatribuição.
- `let`: variável que permite reatribuição.
- `Number()`: conversão de valores para números.

**Manipulação de elementos:**

```javascript
document.getElementById("resultado");
document.querySelector('input[name="operacao"]:checked');
```

**Eventos:**

```javascript
botao.addEventListener("click", function() {
  alert("Botão clicado!");
});
```

**Condicionais e operações:**

```javascript
if (valor1 > valor2) {
  alert("Primeiro valor maior.");
} else {
  alert("Segundo valor maior ou igual.");
}

switch (operacao) {
  case "soma":
    resultado = valor1 + valor2;
    break;
  case "subtracao":
    resultado = valor1 - valor2;
    break;
  case "multiplicacao":
    resultado = valor1 * valor2;
    break;
  case "divisao":
    resultado = valor1 / valor2;
    break;
}
```

**Outros conceitos:** `.value`, `alert()`, `return` e `addEventListener()`.

**Atividade prática — Calculadora de operações:**
- Receber dois valores numéricos.
- Selecionar uma operação matemática.
- Realizar soma, subtração, multiplicação e divisão.
- Verificar o preenchimento dos campos e a operação selecionada.
- Apresentar o resultado na página.

## Aula 10 — Estruturas de repetição e funções

Aprofundamento em JavaScript, trabalhando data e hora, entrada de dados, condições, repetições e funções seta.

**Data e hora:**

```javascript
const dataHora = new Date();
const hora = dataHora.getHours();
```

- `new Date()`: obtém data e hora atuais.
- `getHours()`: retorna a hora atual, de 0 a 23.

**Entrada e tratamento de dados:**

```javascript
let previsaoTempo = prompt("Como está o dia hoje?");
previsaoTempo = previsaoTempo.toLowerCase().trim();
```

- `prompt()`: recebe informações do usuário.
- `toLowerCase()`: transforma texto em minúsculas.
- `trim()`: remove espaços das extremidades.

**Estruturas condicionais:**

```javascript
if (hora < 12) {
  alert("Bom dia!");
} else if (hora < 18) {
  alert("Boa tarde!");
} else {
  alert("Boa noite!");
}
```

**Laços de repetição — for:**

```javascript
for (let contador = 0; contador < 10; contador++) {
  console.log(contador);
}
```

Estrutura: inicialização (`let contador = 0`), condição (`contador < 10`) e incremento (`contador++`).

**Manipulação de conteúdo HTML:**

```javascript
const resultado = document.getElementById("resultado");
resultado.innerHTML = "<p>Olá, mundo!</p>";
```

**Template Strings:**

```javascript
const nome = "Guilherme";
resultado.innerHTML = `Olá, ${nome}!`;
```

**Funções seta — Arrow Functions:**

```javascript
const boasVindas = () => {
  return "Olá, obrigado por visitar nossa página!";
};

botao.addEventListener("click", () => {
  resultado.innerHTML = `${boasVindas()}`;
});
```

**Atividades práticas:**
- Horário e previsão do tempo: data, saudação por horário, `prompt()` e condições.
- Contador de 0 até 9: laço `for`, incremento e exibição com `innerHTML`.
- Funções seta: criação de funções, retorno de mensagens e eventos de clique.

## Aula 11 — Bootstrap 5 e Cards

Introdução ao framework Bootstrap 5 para facilitar a estilização e a criação de interfaces responsivas.

**Importação via CDN:**

```html
<link rel="stylesheet"
 href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.8/dist/css/bootstrap.min.css">
```

**Sistema de Grid:**

```html
<div class="row g-5">
  <div class="col-12 col-md-6">
    <!-- Primeiro card -->
  </div>
  <div class="col-12 col-md-6">
    <!-- Segundo card -->
  </div>
</div>
```

- `row`: cria uma linha.
- `g-5`: define espaçamento entre elementos.
- `col-12`: ocupa 12 colunas.
- `col-md-6`: ocupa 6 colunas em telas médias ou maiores.

**Principais classes:**

| Classe | Função |
|---|---|
| `container` | Centraliza e limita o conteúdo |
| `py-4` | Espaçamento vertical |
| `mb-4` | Margem inferior |
| `text-center` | Centraliza o texto |
| `bg-light` | Fundo claro |
| `card` | Cria um cartão |
| `card-body` | Área interna do cartão |
| `card-title` | Título do cartão |
| `card-text` | Texto do cartão |
| `h-100` | Ocupa 100% da altura disponível |
| `btn-primary` | Botão azul |
| `btn-success` | Botão verde |

**Atividade prática — Organizando Cards:**

Desenvolvimento de uma página chamada "Aprendendo Front-End", contendo cards informativos sobre HTML e CSS, utilizando Grid, componentes Bootstrap, botões, links e responsividade.

---

## Resumo geral das tecnologias

| Tecnologia | Aplicação |
|---|---|
| HTML5 | Estruturação de páginas |
| CSS3 | Estilização e organização de layouts |
| JavaScript | Interatividade e lógica de programação |
| Bootstrap 5 | Componentes e layouts responsivos |

## Objetivo do repositório

Documentar o aprendizado e a evolução prática em Desenvolvimento Front-End para Web, reunindo conteúdos estudados, exemplos de código e atividades realizadas durante a disciplina.

**Tecnologias:** HTML5, CSS3, JavaScript e Bootstrap 5.

**Linguagem:** Português (Brasil).
