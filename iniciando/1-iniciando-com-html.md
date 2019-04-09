# Iniciando com HTML

Não vou me prolongar muito em HTML (HyperText Markup Language), já que não é o foco desse repositório (quem sabe em um outro repositório :P). Vou deixar alguns links para continuação também e sempre me coloco à disposição para quaisquer dúvidas e informações.

A estrutura básica de HTML é composta por **tags** que são abertas e, normalmente, fechadas. A sintaxe da tag é:

```html
<p class="nome-da-classe">Texto desse parágrafo</p>
```

Esse código criará um **p** arágrafo com a classe *nome-da-classe*. Ao invés de classe, poderíamos ter outro [atributo](https://html.com/attributes) e poderíamos usar outra [tag](https://html.com/tags/) ao invés de `<p>`.

Fora `div` e `span`, que são as tags neutras do HTML, todas as classes representam algo na estrutura da página e é recomendado sempre tentar usar a tag que melhor se encaixa no que o seu elemento é dentro do contexto. Por exemplo, pode ser um título (`h1` a `h6`), um parágrafo (`p`), uma imagem (`img`) e assim por diante.

> É importante sempre lembrar que o HTML é uma linguagem de marcação responsável pelo **conteúdo** da página. Dito isso, tudo que for relacionado a estilo deve ser feito com CSS, ou seja, coloca a tag certa (mesmo que ela não tenha o estilo que você quer) e ajusta o estilo com CSS.
> Ainda nisso, é importante lembrar para **não usar a tag `<br>` para espaçamento**! Ajuste esse espaçamento que você precisa com CSS.

Deixei alguns exercícios de estrutura html [aqui](../exercicios/1-1-reconhecendo-estruturas-html.md) com o objetivo de entender melhor as tags por trás do layout.
