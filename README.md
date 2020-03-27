![Markdown course][logo]

# **Markdown**

> Value your project (Valorize o seu projeto).

**[Markdown](https://daringfireball.net/projects/markdown/)** é uma linguagem de marcação criada por **Jonh Gruber** e **[Aaron Swartz](https://pt.wikipedia.org/wiki/Aaron_Swartz)**. Markdown converte seu texto em **[HTML](https://developer.mozilla.org/docs/Web/HTML)** válido.

A ideia desse projeto, é tentar passar o pouco apreendido para ajudar a comunidade no apredizado dessa linguagem de marcação que é tão importante para valorizar os nossos projetos.

## **Índice**

* **[Títulos](https://github.com/zander-br/markdown-course#t%C3%ADtulos)**

* **[Parágrafos](https://github.com/zander-br/markdown-course#p%C3%A1ragrafos)**

* **[Ênfase](https://github.com/zander-br/markdown-course#%C3%AAnfase)**

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


***
## **Páragrafos**

Adicionarmos páragrafos no nosso **Markdown** não poderia ser mais fácil, basta apenas adicionarmos o texto que quermos e pronto.

```markdown
Lorem ipsum dolor sit amet, consectetur adipiscing elit.
```

* **_Resultado_**

Lorem ipsum dolor sit amet, consectetur adipiscing elit.

Porém a única coisa que devemos nos preocupar é que se queremos quebrar linha no nosso texto não basta apenas adicionarmos **Enter** ao código, mais sim adicionarmos dois espaços em branco na linha que queremos quebrar.

```markdown
Lorem ipsum dolor sit amet, consectetur adipiscing elit.  
Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.  
```

* **_Resultado_**

Lorem ipsum dolor sit amet, consectetur adipiscing elit.  
Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

Outra coisa que podemos querer fazer, é adicionarmos um espaço entre um páragrafo e outro, e para isso devemos apenas adicionar dois **Enter** no começo do texto que queremos quebrar.

```markdown
Lorem ipsum dolor sit amet, consectetur adipiscing elit.


Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
```

* **_Resultado_**

Lorem ipsum dolor sit amet, consectetur adipiscing elit.


Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

***
## **Ênfase**

Ênfase é um recurso muito importante, quando queremos destacar algo, ou fazer com que o nosso leitor dê uma maior atenção para aquela palavra um trecho de texto.

No **Markdown** temos várias opções que podemos utilizar para dar ênfase, ou para fazer alguma citação no nosso código, sendo elas.

* [Negrito](https://github.com/zander-br/markdown-course#negrito)

* [Itálico](https://github.com/zander-br/markdown-course#ital%C3%ADco)

* [Tachado (Riscado)](https://github.com/zander-br/markdown-course#tachado-riscado)

* [Citação](https://github.com/zander-br/markdown-course#cita%C3%A7%C3%A3o)

Podemos usar essas opções individualmente, ou em conjunto para alcançarmos um resultado ainda mais legal.

### Negrito

Para adicionarmos negrito temos duas opções, ou usamos dois asteriscos `**` ou também podemos utilizarmos de dois underline `__`. Ambos devem ser colocados no começo e no final do trecho que queremos destacar.

```markdown
**Lorem**, ipsum dolor sit amet, consectetur.


__Lorem__, ipsum dolor sit amet, consectetur.
```

* **_Resultado_**

**Lorem**, ipsum dolor sit amet, consectetur.


__Lorem__, ipsum dolor sit amet, consectetur.

### Itálico

Assim como no negrito, no itálico também temos duas opções para adicionarmos, podendo usar um asteriscos `*` ou também podemos usar de um underline `_`. Ambos devem ser colocados no começo e no final do trecho que queremos destacar.

```markdown
*Lorem*, ipsum dolor sit amet, consectetur.


_Lorem_, ipsum dolor sit amet, consectetur.
```

* **_Resultado_**

*Lorem*, ipsum dolor sit amet, consectetur.


_Lorem_, ipsum dolor sit amet, consectetur.

### Tachado (Riscado)

Para adicionarmos uma palavra ou um trecho de um texto como tachado (riscado) devemos utilizar dois acentos til `~~` no começo e no final do trecho que queremos destacar.

```markdown
~~Lorem~~, ipsum dolor sit amet, consectetur.
```

* **_Resultado_**

~~Lorem~~, ipsum dolor sit amet, consectetur.

### Citação

Caso queremos realizar alguma citação em nosso **Markdown** podemos utilizar o sinal de maior que `>` no começo do parágrafo seguido de um espaço para que possamos destaca-lo.

```markdown
> A vingança nunca é plena malta a alma e envenena
```

* **_Resultado_**

> A vingança nunca é plena malta a alma e envenena.

Para que possamos adicionar negrito e itálico em uma mesma palavra por exemplo, podemos usar três asteriscos `***` ou três underlines `___`, porém o mais utilizado pela comunidade são as combinações `**_Lorem_**` ou `__*Lorem*__`.

***
## **Linhas horizontais**

Linhas horizontais são muito uteis quando queremos realizar alguma separação dos conteúdos para facilitar a leitura. No **Markdown** temos duas opções de fazermos isso, ao qual ambas também possuem pequenas váriações.

```markdown
***
A vingança nunca é plena malta a alma e envenena

---
```

***
A vingança nunca é plena malta a alma e envenena

---

Podemos utilizar de três asteriscos `***` ou de três sinais de menos `---`. Uma variação que podemos usar é adicionarmos espaços entre os asteriscos `* * *` ou entre os sinais de menos `- - -`.

Outra coisa que podemos fazer também caso desejamos é completar toda a linha com asteriscos ou sinais de menos, porém isso é algo totalmente opcional e ao mesmo tempo gera apenas uma estética para o seu arquivo.

> Lembrando que possamos adicionar nossa linha vertical é necessário termos ou três asteriscos ou três sinais de menos com ou sem espaço entre eles.

***

## Listas não ordenadas

Estamos criando ainda. :blush:

***

## Listas ordenadas

Estamos criando ainda. :blush:

***

## Links

Estamos criando ainda. :blush:

***

## Imagens

Estamos criando ainda. :blush:

***

## Tabelas

Estamos criando ainda. :blush:

***

## Códigos

Estamos criando ainda. :blush:

***

## Github

Estamos criando ainda. :blush:

***

[logo]: images/logo.svg