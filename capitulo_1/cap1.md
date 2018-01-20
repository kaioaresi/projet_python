# Introdução a programação em python 3

#### O que é python ?
*Python* é uma linguagem de programação interpretada, orientada a objetos, que é extremamente versátil, existem várias utilizações da mesma em praticamente todo tipo de software, tanto no [Brasil](http://python.org.br/empresas) quanto no [exterior](https://oraculoti.com.br/2017/03/24/quais-sao-as-aplicacoes-mais-famosas-feitas-em-python/).

#### IDEs

Sou um usuário de distribuições GNU/Linux, sendo assim vou falar provavelmente de software voltado ao mesmo, abaixo seque duas ides, o bpython é dinâmico voltado para criar pequenos programas rapinhadamente, já o pycharm é para um desenvolvimento mais complexo, sublime, atom e vim são outras opções bastantes interessantes.

* [Bpython3](https://bpython-interpreter.org/)
* [Pycharm](https://www.jetbrains.com/pycharm/download/#section=linux)
* [Sublime](https://www.sublimetext.com/)
* [Atom](https://atom.io/)
* [Vim](http://www.vim.org/)

Sei que existem várias, porem esses são as que já utilizei ou utilizo, como estou escrevendo sobre minha experiência então, vou falar de apenas o que já usei ou uso.

#### Primeiras impressões

Em um primeiro contato com o *python*, vendo apenas alguns vídeos e lendo o primeiro capítulo do livro, já me surpreendi muito com a clareza da sintaxe da linguagem.

---
### Capítulo - 1

#### Preparando ambiente

* [Linux](http://python.org.br/instalacao-linux)
* [Windows](http://python.org.br/instalacao-windows)


#### Declarações bacias

Bom, vou seguir uma lógica para explicar, algumas coisas primordiais quando se está aprendendo a programar em uma nova linguagem.

Uma listinha de itens que eu acho primordiais para inicia sua jornada em uma nova linguagem.

1. Input e output
2. Declarações de variáveis
3. Operadores matemáticas

> Todos os exemplos serão realizando no meu caso no *bpython3* fique a vontade de usar o que lhe for mais confortável, o importante é ser produtivo.

#### 1 - Input e Output

Em python 3 existe um várias funções importantes, a primeira que vamos conhecer é a função **print()**, a função **print()** é uma função utilizada para exibir dado na tela, segue abaixo documentação oficial:

> Descrição da função [print()](https://docs.python.org/3/tutorial/inputoutput.html) site oficial da função.

**Sintaxe básica**

Basicamente o **print()** recebe um texto e/ou valor/valores e os exibe na tela.

Printando uma texto simples.
# print(<texto>)
```python
print('Olá, mundo')
```

> Vamos diferenciar a saída, só para não fazer o que todo mundo faz quando vai aprender uma nova linguagem, ao invés de "Hello, world" vamos digitar o "Olá, mundo" para ficar diferênte -_- .

Agora trabalhando com variavel.
```python
# print(<variavel>)

nome = 'Kaio Cesar'
print(nome)
```

> **Dica** em python para realizar comentário simples de uma linha usa-se o `#`, para realizar comentários de várias linhas usem o `'''` e fecha com `'''`.

```python
'''
Um texto qualquer que será ignorado pelo interpretador python.
Um texto qualquer que será ignorado pelo interpretador python.
Um texto qualquer que será ignorado pelo interpretador python.
Um texto qualquer que será ignorado pelo interpretador python.
'''
print('Deu certo')
```

---
#### Treino - 1

> Tenho um pensamento que para você aprender qualquer coisa, você deve exercitar, como um músculo se você o exercitar frequentemente para ter resultado, busquei alguns exercícios para garantir se tudo que aprendi até aqui está sendo absorvido corretamento.

> Dúvida é algo comum quando se está aprendendo, se você não tem dúvida é porque você não entendeu direito.















#### 2 - Declaração de vávariavel

Para declarar uma variável em python é basta realizar uma atribuição primeiro o `nome` da variável seguido do sinal `=` mais `valor`, segue exemplo prático abaixo:

```Python
# <nome> = <valor>
nome = 'Kaio Cesar'
```


> Dica: fique sempre atento ao tipo do valor, para não fazer confusão, pois em python existem basicamente três primitivos `String`, `Inteiro` e `Float`, você deve lembrar basicamente em uma String deve estar dentro de `'` ou `"`

---
#### 3. Operadores matemáticas

Em python basicamente é utilizado os operadores convencionais da nossa querida matemática, porém, existem algumas pequenas alterações no modo se declarar o mesmo, segue uma tabelinha para facilitar as coias, ordenados de acordo com a ordem de prioridade de resolução.


Operador | Operação | exemplo | output
:---------: | :----------: | :---------: | :--------:
`**`| Exponecial | 2 ** 3 | 8
`%`| Módulo/resto | 22 % 8 |6
`//`| Divisão inteira | 22 // 8 | 2
`/`| Divisão| 22 / 8 | 2.75
`*`| Multiplicação | 3 * 5 | 15
`-`| Subtração | 5 - 2 | 3
`+`| Soma | 10 + 10 | 20
---


> O operador '**' é o primeiro na ordem de precedência, quando se trata de operadores matemáticos e deve ser o primeiro que de ser resolvido, os demais como `%`,`//`, `/` e `*` possuem a mesma ordem de precedência, porém, a resolução deve ser realizada da esquerda para a direita, demais operadores `-` e `+` ficam por último (também devem ser resolvidos da esquerda para a direita)
