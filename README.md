# desenvovimento-front-end

# Desenvolvimento Front-End para Web

Repositório dedicado à organização dos conteúdos, códigos, exercícios e atividades práticas desenvolvidos durante a disciplina de Desenvolvimento Front-End para Web.

O projeto reúne conhecimentos de HTML5, CSS3, JavaScript e Bootstrap, acompanhando a evolução dos estudos desde a construção de páginas web até o desenvolvimento de interfaces interativas e responsivas.

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
- [Aula 11 — Bootstrap 5 e organização de Cards](#aula-11--bootstrap-5-e-organização-de-cards)

---

## Aula 02 — Títulos, listas e tabelas

Introdução à estruturação de conteúdo utilizando HTML.

### Principais conteúdos

- Estrutura básica de um documento HTML.
- Títulos e subtítulos.
- Parágrafos.
- Listas ordenadas e não ordenadas.
- Criação e organização de tabelas.

### Principais tags

| Tag | Função |
|---|---|
| `h1` até `h6` | Títulos e subtítulos |
| `p` | Parágrafos |
| `ul` | Lista não ordenada |
| `ol` | Lista ordenada |
| `li` | Item de lista |
| `table` | Tabela |
| `tr` | Linha da tabela |
| `th` | Cabeçalho da tabela |
| `td` | Célula da tabela |

---

## Aula 03 — Imagens, tabelas e primeiros estilos

Aprofundamento em HTML, trabalhando com organização de tabelas, inserção de imagens e introdução à estilização.

### Principais conteúdos

- Organização de tabelas com `thead` e `tbody`.
- Inserção de imagens.
- Utilização de `figure` e `figcaption`.
- Introdução ao CSS.
- Primeiros contatos com JavaScript.

### Exemplos

```html
<table>
    <thead>
        <tr>
            <th>Nome</th>
            <th>Idade</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Guilherme</td>
            <td>19</td>
        </tr>
    </tbody>
</table>
```

Inserção de imagens:

```html
<figure>
    <img src="imagem.jpg" alt="Descrição da imagem">
    <figcaption>Legenda da imagem</figcaption>
</figure>
```

---

## Aula 04 — Links e HTML semântico

Utilização de links para navegação entre páginas e introdução aos elementos semânticos do HTML.

### Principais conteúdos

- Criação de links internos e externos.
- Navegação entre páginas.
- Inserção de imagens.
- Utilização de caminhos relativos.
- Organização semântica do documento.
- Estilização de elementos com CSS.

### Principais tags

| Tag | Função |
|---|---|
| `a` | Criação de links |
| `header` | Cabeçalho |
| `nav` | Navegação |
| `section` | Seção de conteúdo |
| `article` | Conteúdo independente |
| `footer` | Rodapé |
| `div` | Agrupamento de elementos |
| `br` | Quebra de linha |
| `hr` | Separador horizontal |

### Exemplo de link

```html
<a href="pagina.html">Acessar página</a>
```

---

## Aula 05 — Áudio, vídeo e formulários

Desenvolvimento de páginas com recursos multimídia e formulários para entrada de informações.

### Principais conteúdos

- Incorporação de vídeos.
- Reprodução de arquivos de áudio.
- Criação de formulários.
- Campos de entrada de dados.
- Botões de envio e limpeza.
- Identificação de campos com labels.

### Áudio

```html
<audio controls>
    <source src="musica.mp3" type="audio/mpeg">
</audio>
```

### Vídeo

```html
<video controls width="400">
    <source src="video.mp4" type="video/mp4">
</video>
```

### Formulários

```html
<form>
    <label for="nome">Nome:</label>
    <input type="text" id="nome" required>

    <label for="email">E-mail:</label>
    <input type="email" id="email" required>

    <button type="submit">Enviar</button>
</form>
```

---

## Aula 06 — CSS externo

Introdução à estilização de páginas HTML utilizando arquivos CSS externos.

### Principais conteúdos

- Integração entre HTML e CSS.
- Criação de arquivos de estilo.
- Seletores CSS.
- Classes para estilização.
- Cores e tipografia.
- Margens e espaçamentos.
- Bordas e alinhamento.

### Integração com CSS externo

```html
<link rel="stylesheet" href="estilo.css">
```

### Exemplo de CSS

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

.paragrafo1 {
    font-family: Arial, sans-serif;
    font-size: 18px;
}
```

### Propriedades estudadas

| Propriedade | Função |
|---|---|
| `color` | Cor do texto |
| `background-color` | Cor de fundo |
| `font-family` | Família da fonte |
| `font-size` | Tamanho da fonte |
| `text-align` | Alinhamento |
| `border` | Borda |
| `padding` | Espaçamento interno |
| `margin` | Espaçamento externo |

---

## Aula 07 — Classes e IDs

Aprofundamento na organização e identificação de elementos HTML utilizando classes e identificadores.

### Classes CSS

São utilizadas para aplicar estilos a um ou mais elementos.

HTML:

```html
<p class="destaque">Texto destacado.</p>
```

CSS:

```css
.destaque {
    color: red;
    font-weight: bold;
}
```

### IDs

Identificam elementos específicos de
