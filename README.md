![Markdown course][logo]

# **Markdown**

> Value your project (Valorize o seu projeto).

**[Markdown](https://daringfireball.net/projects/markdown/)** é uma linguagem de marcação criada por **Jonh Gruber** e **[Aaron Swartz](https://pt.wikipedia.org/wiki/Aaron_Swartz)**. Markdown converte seu texto em **[HTML](https://developer.mozilla.org/docs/Web/HTML)** válido.

A ideia desse projeto, é tentar passar o pouco aprendido para ajudar a comunidade no apredizado dessa linguagem de marcação que é tão importante para valorizar os nossos projetos.

## **Índice**

* **[Títulos](https://github.com/zander-br/markdown-course#t%C3%ADtulos)**

* **[Parágrafos](https://github.com/zander-br/markdown-course#p%C3%A1ragrafos)**

* **[Ênfase](https://github.com/zander-br/markdown-course#%C3%AAnfase)**

* **[Linhas horizontais](https://github.com/zander-br/markdown-course#linhas-horizontais)**

* **[Listas não ordenadas](https://github.com/zander-br/markdown-course#listas-n%C3%A3o-ordenadas)**

* **[Listas ordenadas](https://github.com/zander-br/markdown-course#listas-ordenadas)**

* **[Links](https://github.com/zander-br/markdown-course#links)**

* **[Imagens](https://github.com/zander-br/markdown-course#imagens)**

* **[Tabelas](https://github.com/zander-br/markdown-course#tabelas)**

* **[Códigos](https://github.com/zander-br/markdown-course#c%C3%B3digos)**

* **[Github](https://github.com/zander-br/markdown-course#github)**

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

* [Itálico](https://github.com/zander-br/markdown-course#it%C3%A1lico)

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

* **_Resultado_**
***
A vingança nunca é plena malta a alma e envenena

---

Podemos utilizar de três asteriscos `***` ou de três sinais de menos `---`. Uma variação que podemos usar é adicionarmos espaços entre os asteriscos `* * *` ou entre os sinais de menos `- - -`.

Outra coisa que podemos fazer também caso desejamos é completar toda a linha com asteriscos ou sinais de menos, porém isso é algo totalmente opcional e ao mesmo tempo gera apenas uma estética para o seu arquivo.

> Lembrando que possamos adicionar nossa linha vertical é necessário termos ou três asteriscos ou três sinais de menos com ou sem espaço entre eles.

***

## Listas não ordenadas

Listas não ordenadas é um recurso muito importante, pois permite criarmos tópicos de textos para uma melhor exemplificação sobre determinados assuntos.

Para criarmos listas não ordenadas no **Markdown** é muito simples do que criamos no HTML. Para isso temos duas opções, ou usamos o asterisco `*` ou podemos usar também o sinal de menos `-`, ambos seguidos por espaço entre os itens.

```markdown
Produtos

* Item 01
* Item 02
* Item 03
```

* **_Resultado_**

Produtos

* Item 01
* Item 02
* Item 03

Como informado anteriormente também podemos criar utilizando o sinal de menos `-`.

```markdown
Produtos

- Item 01
- Item 02
- Item 03
```

* **_Resultado_**

Produtos

- Item 01
- Item 02
- Item 03

Caso desejamos criar uma lista não ordenada com subitens também podemos e de maneira simples e fácil, basta na frente de cada subitem adicionarmos um **TAB** ou dois espaços.

```markdown
Sumário

* Item 01
  * SubItem 01
  * SubItem 02
* Item 02
  * SubItem 02
* Item 03
```

* **_Resultado_**

Sumário

* Item 01
  * SubItem 01
  * SubItem 02
* Item 02
* Item 03

***

## Listas ordenadas

Assim com as listas não ordenadas, as listas ordenadas são muito importantes para exemplicação de nossos conteúdos. Da mesma maneira definir listar ordenadas no **Markdown** é algo muito simples.

Para essa criação necessitamos apenas informar o **número** a partir de qual queremos que nossa lista inicie seguida do ponto `.` e do espaço.

```markdown
Sumário

1. Item 01
2. Item 02
3. Item 03
```

* **_Resultado_**

Sumário

1. Item 01
2. Item 02
3. Item 03

Podemos facilmente iniciarmos a nossa contagem a partir de outro número e não necessariamente do número 1.

```markdown
Sumário

8. Item 01
9. Item 02
10. Item 03
```

* **_Resultado_**

Sumário

8. Item 01
9. Item 02
10. Item 03

Mesmo sendo algo extremamente simples de implementarmos as listas ordenadas possuem alguns particularidades.

Caso informamos os mesmos números para todos os itens, a lista automaticamente segue a sequência de forma crescente.

```markdown
Sumário

1. Item 01
1. Item 02
1. Item 03
```

* **_Resultado_**

Sumário

1. Item 01
1. Item 02
1. Item 03

Caso também informamos os itens de maneira desordenada, a lista ordenada irá gerar uma nova sequência baseada no primeiro item da lista.

```markdown
Sumário

8. Item 01
5. Item 02
3. Item 03
```

* **_Resultado_**

Sumário

8. Item 01
5. Item 02
3. Item 03

Com base nessas informações você deve estar se perguntando e caso eu queira fazer uma lista ordenada com a sequência que eu passar para ela? A solução também é bem simples basta colocarmos o número desejado seguido de um caracter de escape e do ponto `\.` e posteriormente do espaço.

```markdown
Campeões da Copa Mundial

1994\. Brasil  
1998\. França  
2002\. Brasil  
```

* **_Resultado_**

Campeões da Copa Mundial

1994\. Brasil  
1998\. França  
2002\. Brasil 

***

## Links

Algo que com certeza não deve faltar em uma boa documentação, são os links pois eles são muito uteis ou para facilitar na navegação durante a leitura do usuário ou para fornecer mais informações importantes para compreensão da mensagem, podendo ser um link para uma guia de instalação ou para outra documentação de outro projeto.

Para criarmos um link no **Markdown** basta informarmos dentro colchetes `[]` o nome que será informado para o usuário de entre parênteses `()` informamos o link.

```markdown
[Instalação GIT](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
```

* **_Resultado_**

[Instalação GIT](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)

Algo que podemos adicionarmos aos nossos links para melhorar a usabilidade são os nomes que aparecerão quando o cursor do mouse estiver por cima do link, para isso basta dentro dos parênteses `()` e posteriormente ao link informado, adicionarmos um espaço e entre aspas duplas `""` informamos o texto desejado.

```markdown
[Instalação GIT](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git "Instalação GIT")
```

* **_Resultado_**

[Instalação GIT](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git "Instalação GIT")

Outra coisa que podemos fazer em nossos links é criarmos uma váriavel contendo a url do mesmo, para isso basta dentro de colchetes `[]` informar o nome da váriavel depois adicionarmos dois pontos `:` e o valor da mesma.

Nessa abordagem a definição de um link muda um pouco ao qual informaremos agora entre colchetes `[]` o nome para o nosso link e novamente dentro dos colchetes `[]` informamos o nome da nossa variável.

```markdown
[Instalação GIT][git-url]

[git-url]:https://git-scm.com/book/en/v2/Getting-Started-Installing-Git
```

* **_Resultado_**

[Instalação GIT][git-url]

[git-url]:https://git-scm.com/book/en/v2/Getting-Started-Installing-Git

***

## Imagens

Algo que enriquece bastante uma documentação sem dúvida são as imagens, podendo ser uma captura de tela que mostra aquele seu layout bacana. Como se dizem uma imagem vale mais que mil palavras.

O processo de inserção de imagens no **Markdown** é bastante semelhante a crianção de um **[Link](https://github.com/zander-br/markdown-course#links)** diferenciando apenas que para as imagens temos que adicionar no começo um sinal de exclamação `!`.

```markdown
![Seu Madruga](images/vinganca.jpg)
```

* **_Resultado_**

![Seu Madruga](images/vinganca.jpg)

Assim com nos **[Links](https://github.com/zander-br/markdown-course#links)** também podemos usar uma váriavel para armazenar o endereço da nossa imagem.

```markdown
![Seu Madruga][vinganca-img]

[vinganca-img]:images/vinganca.jpg
```

* **_Resultado_**

![Seu Madruga][vinganca-img]

[vinganca-img]:images/vinganca.jpg

Algo que podemos adicionar em nossas imagens são os links, ao qual permite que o usuário navegue para a mesma após clicar sobre. E para isso devemos apenas envolver a nossa declaração da imagem `![nome](endereco)` ou `![nome][variavel-endereco]` dentro dos colchetes `[]`, e posteriormente dentro dos meus parênteses `()` ou colchetes `[]` caso estejamos usando váriaveis para nosso link informamos o endereço de destino `[![nome](endereco)](url)`. 

```markdown
[![Seu Madruga](images/vinganca.jpg)](https://github.com/zander-br/markdown-course/blob/master/images/vinganca.jpg)
```

* **_Resultado_**

[![Seu Madruga](images/vinganca.jpg)](https://github.com/zander-br/markdown-course/blob/master/images/vinganca.jpg)

A essa altura você já deve estar se perguntando, mais como faço para alterar o tamanho da minha imagem? Nesse caso o **Markdown** não possui suporte para esse tipo de situação, porém como solução podemos fazer uso da tag `img` do HTML, conforme exemplo abaixo.

```markdown
<img src="images/vinganca.jpg" width="100px;" alt="Henrique Tavares"/>
```

* **_Resultado_**

<img src="images/vinganca.jpg" width="200px;" alt="Seu Madruga"/>

***

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
