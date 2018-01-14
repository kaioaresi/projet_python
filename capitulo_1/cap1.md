# Introdução a programação em python

#### O que é python ?
*Python* é uma linguagem de programação interpretada, orientada a objetos, que é extremamente versátil, existem várias utilizações da mesma em praticamente todo tipo de software, tanto no [Brasil](http://python.org.br/empresas) quanto no [exterior](https://oraculoti.com.br/2017/03/24/quais-sao-as-aplicacoes-mais-famosas-feitas-em-python/).

#### IDEs

Sou um usuário de distribuições GNU/Linux, sendo assim vou falar provavelmente de software voltado ao mesmo.

* [Bpython3](https://bpython-interpreter.org/)
* [Pycharm](https://www.jetbrains.com/pycharm/download/#section=linux)

Eu sei que existem várias, porem está são as que já utilizei, como estou escrevendo sobre minha experiência então, vou falar de apenas o que já usei ou uso.

#### Primeiras impressões

Em um primeiro contato com o *python*, vendo alguns vídeos e lendo o primeiro capítulo do livro, já me surpreendi muito com a clareza da sintaxe da linguagem, estou aprendendo o python 3.


### Capítulo - 1

#### Preparando ambiente

* [Linux](http://python.org.br/instalacao-linux)
* [Windows](http://python.org.br/instalacao-windows)


#### Declarações bacias

Bom, vou seguir uma lógica para explicar, algumas coisas primordiais quando se está aprendendo a programa em uma nova linguagem.

Uma listinha de itens que eu acho primordiais para inicia sua jornada em uma nova linguagem.

1. Input e output
2. Declarações de variáveis
3. operações matematicas

> Todos os exemplos serão realizando no meu caso no *bpython3* fique a vontade de usar o que lhe for mais confortável, o importante é ser produtivo.

#### 1 - Input e Output

Em python 3 existe um várias funções importantes, a primeira que vamos conhecer é a função **print()**, a função **print()** é uma função utilizada para exibir dado na tela, segue abaixo documentação oficial:

> Descrição da função [print()](https://docs.python.org/3/tutorial/inputoutput.html) site oficial da função.

**Sintaxe básica**

Basicamente o **print()** recebe um texto e/ou valor/valores e os exibe na tela.

Printando uma texto simples.
```python
# print(<texto>)
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
