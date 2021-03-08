# Markdown

Aplicando na prática os comandos aprendidos na linguagem ***Markdown***

---
A linguagem **Markdown** assim como o *html* são linguagens de marcação e não de programação. Mas por que motivos utilizaríamos o **Markdown** se nós já temos o *html*?

A linguagem **Markdown** tem como objetivo tornar o código fonte mais legível e de fácil leitura. Além disso ele é utilizado em vários momentos sem que as pessoas saibam, como aqui mesmo no GitHub dentro das "Issues", no arquivo "README.md" que por sinal a extenção ".md" significa **Markdown**, no aplicativo de voz Discord e até mesmo o whatsapp tem comandos com base em **Markdown**.

Mas chega de enrolação, vamos aprender a utilizar os comandos...

Vocês podem baixar este arquivo para visualizar o código fonte do mesmo e entender melhor cada um dos comandos que forem listados aqui.

## Códigos em Markdown

### Negrito

Para deixar um texto ou parte de um texto em **negrito**, nós podemos utilizar o síbolo asterisco duas vezes `**` no início, depois devemos utilizar o mesmo símbolo para indicar que queremos terminar o texto ou a palavra em negrito, do contrário este efeito seria aplicado para todo o texto.

Nós também podemos ao inves de asterísco, utilizar o underline DUAS vezes `__` no início, para indicar que desejamos iniciar o efeito __negrito__ e duas vezes no final, para indicar que desejamos encerrar o efeito.

`**teste**` ou `__teste__`

### Itálico

Para adicionar o efeito *Itálico*, nós podemos utilizar o asterísco apenas uma vez `*` ao inves de duas como vimos no negrito.

Assim como em negrito, nós devemos adicionar o símbolo no início da frase ou texto que desejamos deixar em _itálico_ e depois utilizamos novamente para encerrar o efeito para que o mesmo não seja aplicado em toda a extenção do texto sem que seja de nossa vontade.

Nós também podemos utilizar o underline `_` UMA vez, para substituir o asterísco, pois o efeito aplicado é o mesmo.

`*teste*` ou `_teste_`

### Texto riscado

As vezes nós queremos riscar alguma parte do texto e o comando **Markdown** utilizado para essa finalidade é o til `~~`. Nós utilizamos ele DUAS vezes antes da frase para indicar o início do efeito e depois utilizamos mais duas vezes para indicar o encerramento do mesmo.

`~~teste~~`

### Títulos

Os títulos são representados pelas __*Hashtags*__.

Nós utilizamos UMA hashtag `#` para indicar um título de **Nível 1**, DUAS hashtags `##` para indicar um título de **Nível 2** e TRÊS hashtags `###` para indicar um título de **Nível 3**.

```
# Título nível 1
## Título nível 2
### Título nível 3
```

### Linhas horizontais

Para criarmos linhas horizontais nós utilizamos TRÊS sinais de menos `---` OU TRÊS asteríscos `***`. 

Assim podemos criar uma linha horizontal (bem marcada) para separar ou dividir tópicos por exemplo.

`---` ou `***`

### Misturar efeitos

Outra coisa que podemos fazer em ~~**_Markdown_**~~ é misturar os efeitos como negrito, sublinhado e riscado. Exemplo:

`~~**_Markdown_**~~`

### Lista numerada

```
1. teste1
1. teste2
1. teste3
5. teste4
```

1. teste1
1. teste2
1. teste3
5. teste4

Caso deseje criar listas como esta, também é possível através da linguagem **Markdown**. Basta adicionar um número como o número 1 por exemplo, seguido de um ponto final, espaço, e o texto.

Independente da numeração que você utilizar para criar a lista, ela será ordenada da forma correta como no exemplo acima.

Você também pode adicionar sub-itens na lista numerada, por exemplo:

```
1. teste
   1. teste1.1
   2. teste1.2
```

1. teste
   1. teste1.1
   2. teste1.2

Basta adicionar TRÊS espaços antes de adicionar o número e o ponto final.

### Listas demarcadas

As listas demarcadas podem ser criadas utilizando o símbolo asterísco `*` ou o sinal de menos `-`, seguido de espaço e o texto.

```
* teste
* teste2
* teste3
```

* teste
* teste2
* teste3

Nesta lista nós também podemos adicionar sub-itens. Basta adicionarmos TRÊS espaços, o símbolo ou o sinal de menos e o texto.

```
* teste
   * teste1.1
   * teste1.2
```

* teste
   * teste1.1
   * teste1.2

### Lista de tarefas

A lista de tarefas é muito útil e tem sido muito utilizada. Para criarmos uma lista deste tipo nós utilizamos o sinal de menos `-` seguido de espaço,  abertura de colchetes, espaço, fechamento de colchetes, espaço, e o texto que desejamos.

```
- [ ] teste
- [ ] teste2
- [ ] teste3
```

- [ ] teste
- [ ] teste2
- [ ] teste3

Suponhamos que você cumpriu uma ou todas estas tarefas, como marcar esta tarefa na lista?

Muito simples. Basta você substituir o espaço entre os colchetes pela letra "X" e a marcação será feita.

```
- [x] teste
- [x] teste2
- [ ] teste3
```

- [x] teste
- [x] teste2
- [ ] teste3

Assim como nas listas anteriores, nós também podemos adicionar sub-itens a esta lista. Para isso nós só precisamos fazer como nas listas anteriores e adicionar os TRÊS espaços antes do comando.

```
- [ ] teste
   - [x] teste1.1
   - [ ] teste1.2 
```

- [ ] teste
   - [x] teste1.1
   - [ ] teste1.2 

### Adicionando imagens

Adicionar imagens a linguagem **Mardown** também é muito simples. 

Primeiro adicionamos o sinal de exclamação `!` seguido da abertura de colchetes `[`, descrição da imagem , fechamento de colchetes `]`, abertura de parênteses `(`, o link web da imagem desejada ou o endereço local da mesma, e por fim o fechamento dos parênteses `)`.

`![teste](img/imagem.png)`

`![teste](https://algumacoisa.png)`

![My Job](https://user-images.githubusercontent.com/44281496/110272857-ef8b0c80-7fa9-11eb-9d84-f24a6da689d0.jpg)

### Adicionar links

A sintaxe para adicionar links é a mesma de inserir imagens, porém sem o ponto de exclamação `!`.

`[teste](https://link.com.br)`

[Portifólio da imagem acima](https://www.behance.net/gallery/99906159/Pride-is-Red)
