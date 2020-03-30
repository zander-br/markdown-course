![Markdown course][logo]

# **Markdown**

> Value your project (Valorize o seu projeto).

**[Markdown](https://daringfireball.net/projects/markdown/)** é uma linguagem de marcação criada por **Jonh Gruber** e **[Aaron Swartz](https://pt.wikipedia.org/wiki/Aaron_Swartz)**. Markdown converte seu texto em **[HTML](https://developer.mozilla.org/docs/Web/HTML)** válido.

A ideia desse projeto, é tentar passar o pouco aprendido para ajudar a comunidade no apredizado dessa linguagem de marcação que é tão importante para valorizar os nossos projetos.

## **Índice**

* **[Títulos](#t%C3%ADtulos)**

* **[Parágrafos](#p%C3%A1ragrafos)**

* **[Ênfase](#%C3%AAnfase)**

* **[Linhas horizontais](#linhas-horizontais)**

* **[Listas não ordenadas](#listas-n%C3%A3o-ordenadas)**

* **[Listas ordenadas](#listas-ordenadas)**

* **[Links](#links)**

* **[Imagens](#imagens)**

* **[Tabelas](#tabelas)**

* **[Códigos](#c%C3%B3digos)**

* **[Github](#github)**

* **[Extra](#extras)**

* **[Referências](#refer%C3%AAncias)**

* **[Dicas](#dicas)**

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

* [Negrito](#negrito)

* [Itálico](#it%C3%A1lico)

* [Tachado (Riscado)](#tachado-riscado)

* [Citação](#cita%C3%A7%C3%A3o)

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

O processo de inserção de imagens no **Markdown** é bastante semelhante a crianção de um **[Link](#links)** diferenciando apenas que para as imagens temos que adicionar no começo um sinal de exclamação `!`.

```markdown
![Seu Madruga](images/vinganca.jpg)
```

* **_Resultado_**

![Seu Madruga](images/vinganca.jpg)

Assim com nos **[Links](#links)** também podemos usar uma váriavel para armazenar o endereço da nossa imagem.

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
<img src="images/vinganca.jpg" width="100px;" alt="Seu Madruga"/>
```

* **_Resultado_**

<img src="images/vinganca.jpg" width="100px;" alt="Seu Madruga"/>

***

## Tabelas

Outra coisa que temos disponível no **Markdown** e nos auxilia bastante nas nossas documentações são as tabelas, com elas podemos demostrar o retorno de alguma informação, organizar as dependências do projetos com links para seus respectivos repositórios e por aí vai.

E para criarmos as nossas tabelas no **Markdown** não poderia ser mais simples basta encapsularmos nossos valores das colunas dentro de um pipe `|` da seguinte forma `| coluna |` colocando sempre um espaço entre os pipes e o conteúdo. Uma pequena atenção que precisamos ter é que no caso dos cabeçalhos da tabela na próxima linha subsequente devemos adicionar um sinal de menos `-` representando as colunas. Com o exemplo tudo irá ficar mais simples.

```markdown
| Nome | Idade |
| - | - |
| Anderson | 30 |
```

* **_Resultado_**

| Nome | Idade |
| - | - |
| Anderson | 30 |

Opcionalmente podemos alinharmos o pipe `|` no nosso documento, porém isso não gera resultado diferente na documentação, apenas algo estético.

```markdown
| Nome     | Idade |
| -------- | ----- |
| Anderson | 30    |
```

* **_Resultado_**

| Nome     | Idade |
| -------- | ----- |
| Anderson | 30    |

Mais como fica em tabelas maiores? Montei um examplo um pouco maior para demostrar o resultado.

```markdown
| Nome | Idade | Profissão |
| ---- | ----- | --------- |
| Anderson Santos | 30 | Programador |
| Alvo Dumbledore | 150 | Diretor |
| McGonagall | 70 | Professora |
```

* **_Resultado_**

| Nome | Idade | Profissão |
| ---- | ----- | --------- |
| Anderson Santos | 30 | Programador |
| Alvo Dumbledore | 150 | Diretor |
| McGonagall | 70 | Professora |

Caso seja necessário também, podemos utilizar alinhamentos em nossas tabelas, e para fazermos isso basta adicionarmos sinal de dois pontos `:` na  linha que vem logo após o cabeçalho e juntamente com o sinal de menos `-`.

Para alinhamentos a esquerda basta adicionarmos o sinal de dois pontos no lado esquerdo do sinal de menos `:-`, para alinhamentos a direita posicionamentos a direita `-:` e para alinhamentos ao centro colocamos o sinal de menos entre o sinal de dois pontos `:-:`. Simples assim, mais de qualquer forma vamos demostrar no exemplo abaixo.

```markdown
| Nome (esquerda) | Idade (centro) | Profissão (direita) |
| :-------------- | :------------: | ------------------: |
| Anderson Santos |       30       |     Programador     |
| Alvo Dumbledore |       150      |       Diretor       |
| McGonagall      |       70       |      Professora     |
```

* **_Resultado_**

| Nome (esquerda) | Idade (centro) | Profissão (direita) |
| :-------------- | :------------: | ------------------: |
| Anderson Santos |       30       |     Programador     |
| Alvo Dumbledore |       150      |       Diretor       |
| McGonagall      |       70       |      Professora     |

***

## Códigos

Chegamos agora em um ponto que é extremante importante para uma boa documentação, principamente para bibliotecas, projetos de código aberto, e sem sombra de dúvida estamos falando dos exemplos de códigos para ajudar aquele nosso amiguinho.

No **Markdown** demos duas forma de demostrar nosso código, podendo ser *inline*, ou seja, na própria linha que estamos escrevendo, ou criando um bloco de códigos. Também temos um pequeno plus que são o **_Syntax Highlighting_** essa opção sem dúvida é a cereja do bolo.

* [Inline](#inline)

* [Bloco](#bloco)

* [Syntax Highlighting](#syntax-highlighting)

### Inline

Como já comentado anteriormente a inserção de códigos *inline* (na linha) é muito importante quando estamos decorrendo sobre um determinado assunto e queremos informar um pequeno trecho de código, ou uma chamada de um metódo ou função.

Para que possamos adicionar um código *inline* no **Markdown** basta que informamos o mesmo dentro do acento de grave ``(`)`` representado aqui dentro dos parânteses.

```markdown
Passe o `username` e `password` como parâmetros para a função `login()`.
```
* **_Resultado_**

Passe o `username` e `password` como parâmetros para a função `login()`.

Em linguagens como por exemplo o **[JavaScript](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript)** temos uma funcionalidade nas strings chamado **[Template string](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Reference/template_strings)** que faz uso do acento grave para realizar concatenação de textos.

Nesse caso devemos fazer o escape de caracteres para que possamos conseguir o mesmo resultado.

```markdown
``const message = `My name is ${name}`;``
```
* **_Resultado_**

``const message = `My name is ${name}`;``

> O exemplo acima foi desenvolvido utilizando a linguagem **[JavaScript](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript)** assim como os exemplos subsequentes. 

### Bloco

Muitas vezes o que queremos fazer é mostrar uma grande qualidade de código, para que façamos isso também é muito simples, e temos mais que uma opção para alcançar o mesmo resultado.

A primeira opção é na frente do bloco de código que queremos adicionar, inserirmos dois `TABs` ou quatro espaços.

```markdown
    // login.js

    const username = 'zander-br';
    const password = 'secret';

    login(username, password);
```
* **_Resultado_**

```
// login.js

const username = 'zander-br';
const password = 'secret';

login(username, password);
```

Porém a forma mais usada pela comunidade é o uso de três assentos graves antes do código (uma linha acima) e depois do código (uma linha abaixo).

<pre lang="no-highlight"><code>```
  // login.js


  const username = 'zander-br';
  const password = 'secret';


  login(username, password);
```
</code></pre>

* **_Resultado_**

```
  // login.js


  const username = 'zander-br';
  const password = 'secret';


  login(username, password);
```

### Syntax Highlighting


Como comentado anteriormente, chegamos agora a cereja do bolo, pois o uso de *Syntax Highlighting* não somente cria para nós uma bloco de código como também realça o mesmo com cores.

```javascript
  // login.js


  const username = 'zander-br';
  const password = 'secret';


  login(username, password);
```

O que achou desse código? Legal né? Você deve estar se perguntando qual a mágica que foi usada aqui, ou então afirmando... Isso deve ser muito dificil de fazer.

Se se eu falar que tudo que você deve fazer é informar na frente dos três primeiros acentos graves o nome da linguagem e caixa baixa.

<pre lang="no-highlight"><code>```javascript
  // login.js


  const username = 'zander-br';
  const password = 'secret';


  login(username, password);
```
</code></pre>

* **_Resultado_**

```javascript
  // login.js


  const username = 'zander-br';
  const password = 'secret';


  login(username, password);
```

Nesse momento você deve estar falando, mais isso funciona apenas para javascript... Então o que acha desse trecho de código em **[Ruby](https://www.ruby-lang.org/)**.

<pre lang="no-highlight"><code>```ruby
require 'redcarpet'
markdown = Redcarpet.new("Hello World!")
puts markdown.to_html
```
</code></pre>

* **_Resultado_**

```ruby
require 'redcarpet'
markdown = Redcarpet.new("Hello World!")
puts markdown.to_html
```

Muito legal né? Porém você deve informar apenas uma liguagem por blocos de códigos. Outra dica interessante é que no caso do **[JavaScript](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript)** podemos usar `javascript` ou simplesmente `js`.

***

## Github

E para finalizar vou dar algumas dicas sobre o uso de **Markdown** no **[GitHub](https://github.com/)** que irá turbinar ainda mais o seus conhecimentos e também ajudar ainda mais nas suas contribuições.

No **[GitHub](https://github.com/)** podemos fazer uso de emojis :heart_eyes: é isso mesmo que você entendeu você pode adicionar emojis tanto em mensagens de commits, quanto no seu **README.md** e também nas *Issues* do **[GitHub](https://github.com/)**.

Para isso basta adicionar entre dois pontos `:` o nome do emoji que deseja adicionar. E para facilitar a sua vida estarei deixando aqui uma lista com todos esses emojis **[Emoji Cheat Sheet](https://www.webfx.com/tools/emoji-cheat-sheet/)**.

```markdown
Estou estou :heart_eyes: esse conteúdo, simplesmente ficou show! :relaxed:
```
* **_Resultado_**

Estou amando :heart_eyes: esse conteúdo, simplesmente ficou show! :relaxed:

Outra coisa que podemos fazer é adicionarmos uma lista de **Todo** das pendências ou coisas que precisam ser desenvolvidas em uma *issues*. Para isso basta adicionar dois colchetes `[]` e entre eles adicionar um espaço. Caso o item tenha sido finalizado basta adiconar uma letra `x`.

```markdown
Curso de markdown no Github

* [x] Estudar sobre markdown :books:
* [ ] Deixar uma estrela no repositório :star:
* [ ] Indicar para os meus amigos :family:
```
* **_Resultado_**

Curso de markdown no Github

* [x] Estudar sobre markdown :books:
* [ ] Deixar uma estrela no repositório :star:
* [ ] Indicar para os meus amigos :family:

***

## Extras

Algo que não foi mencionado durante esse conteúdo por não se tratar de algo nativo no **Markdown**, porém que muitas vezes acabamos querendo usar para deixar as nossas documentações mais bonitas e atrativas, são os alinhamentos de conteúdos.

No **Markdown** não temos maneira de fazermos o aninhamento dos conteúdos, porém como mencionado inicialmente na introdução do conteúdo, o **Markdown** converte o seu texto em HTML válido, ou seja, assim como na seção de [Imagens](#imagens) podemos fazer uso de tags HTML para extender as funcionalidades do **Markdown**.

Por isso para conseguirmos alinharmos nossos conteúdos em nossas documentações podemos HTML para isso conforme exemplos abaixo.

```markdown
<p align="center">
  <img src="images/vinganca.jpg" width="100px;" alt="Seu Madruga"/>
</p>
<p align="center">"Eu prefiro morrer que perder a vida"</p>
```

* **_Resultado_**

<p align="center">
  <img src="images/chaves.jpg" alt="Chaves"/>
</p>
<p align="center">"Eu prefiro morrer que perder a vida"</p>

Acima temos o alinhamento de conteúdos ao centro, nota que não usamos uma **div** pois o alinhamento na div não funciona no [GitHub](https://github.com/).

```markdown
<p align="right">
  <img src="images/vinganca.jpg" width="100px;" alt="Seu Madruga"/>
</p>
<p align="right">"Eu prefiro morrer que perder a vida"</p>
```

* **_Resultado_**

<p align="right">
  <img src="images/chaves.jpg" alt="Chaves"/>
</p>
<p align="right">"Eu prefiro morrer que perder a vida"</p>

Da mesma forma também podemos fazer o alinhamento dos conteúdos a direita, mudando apenas a propriedade `align=right`. O alinhamento a esquerda é padrão do **Markdown** então podemos continuar usando nessas situações.

***

## Referências

Como informado no começo desse conteúdo, a ideia desse repositório surgiu para ajudar na fixação dos conteúdos que eu estava estudando e de quebra ajudar mais pessoas :relaxed: então para isso eu usei alguns materiais, caso queira dar uma olhada segue os links abaixo.

* **[Site oficial de Markdown](https://daringfireball.net/projects/markdown)**

* **[Markdown-Here](https://github.com/adam-p/markdown-here)**

* **[Creating and highlighting code blocks](https://help.github.com/en/github/writing-on-github/creating-and-highlighting-code-blocks)**

* **[Aprenda Markdown](https://www.udemy.com/course/aprenda-markdown/)**

* **[Guia básico de Markdown](https://docs.pipz.com/central-de-ajuda/learning-center/guia-basico-de-markdown#open)**

* **[Changing image size in Markdown](https://stackoverflow.com/questions/14675913/changing-image-size-in-markdown)**

***

## Dicas

E por fim, queria deixar uma dica muito legal do [Willian Justen](https://github.com/willianjusten) para você que precisa de uma ideia de **README.md** aqui [Awesome README](https://github.com/matiassingers/awesome-readme) você irá encontrar vários examplos, basta escolher o que mais agrada você.

Caso você prefira um template de **README.md**, fica uma dica muito legal de um gist da [PurpleBooth](https://gist.github.com/PurpleBooth/109311bb0361f32d87a2).

Uma dica que não está relacionado a **Markdown** mais como todos projetos precisam, fica mais como um plus. Caso você precise de um arquivo de licença nesse site irá lhe ajudar nessa tarefa [Open Source Initiative](https://opensource.org/licenses)

[logo]: images/logo.svg
