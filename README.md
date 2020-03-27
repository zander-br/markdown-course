![Markdown course][logo]

# **Markdown**

> Value your project (Valorize o seu projeto).

**[Markdown](https://daringfireball.net/projects/markdown/)** é uma linguagem de marcação criada por **Jonh Gruber** e **[Aaron Swartz](https://pt.wikipedia.org/wiki/Aaron_Swartz)**. Markdown converte seu texto em **[HTML](https://developer.mozilla.org/docs/Web/HTML)** válido.

A ideia desse projeto, é tentar passar o pouco apreendido para ajudar a comunidade no apredizado dessa linguagem de marcação que é tão importante para valorizar os nossos projetos.

## **Índice**

* **[Títulos](https://github.com/zander-br/markdown-course#t%C3%ADtulos)**

* Parágrafos

* Ênfase

* Linhas horizontais

* Listas não ordenadas

* Listas ordenadas

* Links

* Imagens

* Tabelas

* Códigos

* Github

## Títulos

O títulos são muito importantes para que possamos organizar os nossos documentos, e no Markdown não é diferente.

Para nos auxiliar na criação de uma documentação elegante, assim como o HTML o Markdown fornece uma 6 herarquia de títulos similares ao h1 a h6 no HTML.

Para criarmos um título basta utilizarmos `# Título` (hashtag + espaço + Título), ao qual conforme quantidade de `#` que usamos corresponde a herarquia de nosso título, conforme example abaixo.

```markdown
# Título 1 (h1)
## Título 2 (h2)
### Título 3 (h3)
#### Título 4 (h4)
##### Título 5 (h5)
###### Título 6 (h6)
```

* **_Resultado_**

# Título 1 (h1)
## Título 2 (h2)
### Título 3 (h3)
#### Título 4 (h4)
##### Título 5 (h5)
###### Título 6 (h6)

Podemos adicionar a nossa `#` opcionalmente no final de cada título `# Título #`, mais isso seria algo mais estético.

Somente para o "h1" e "h2" podemos adicionar conforme exemplo abaixo, porém pouco usado.

```markdown
Título 1 (h1)
=

Título 2 (h2)
-
```

> Para o Título 1 (h1) na próxima linha subsequente adicionamos o sinal de igual `=`, já para o nosso Título 2 (h2) na linha subsequente adicionamos o sinal de menos `-`.


## **Páragrafos**

Adicionarmos páragrafos no nosso **Markdown** não poderia ser mais fácil, basta apenas adicionarmos o texto que quermos e pronto.

```markdown
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua
```

* **_Resultado_**

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua

Porém a única coisa que devemos nos preocupar é que se queremos quebrar linha no nosso texto não basta apenas adicionarmos **Enter** ao código, mais sim adicionarmos dois espaços em branco na linha que queremos quebrar.

```markdown
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.  
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
```

* **_Resultado_**

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.  
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

Outra coisa que podemos querer fazer, é adicionarmos um espaço entre um páragrafo e outro, e para isso devemos apenas adicionar dois **Enter** no começo do texto que queremos quebrar.

```markdown
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.


Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
```

* **_Resultado_**

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.


Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

[logo]: images/logo.svg