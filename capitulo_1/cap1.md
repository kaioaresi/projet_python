# Introdução a programação em python

#### O que é python ?
*Python* é uma linguagem de programação interpretada, orientada a objetos, que é extremamente versátil, existem várias utilizações da mesma em praticamente todo tipo de software, tanto no [Brasil](http://python.org.br/empresas) quanto no [exterior](https://oraculoti.com.br/2017/03/24/quais-sao-as-aplicacoes-mais-famosas-feitas-em-python/).

#### IDEs

Sou um usuário de distribuições GNU/Linux, sendo assim vou falar provavelmente de software voltado ao mesmo.

* [Bpython3](https://bpython-interpreter.org/)
* [Pycharm](https://www.jetbrains.com/pycharm/download/#section=linux)

Eu sei que existem várias, porem está são as que já utilizei, como estou escrevendo sobre minha experiência então, vou falar de apenas o que já usei ou uso.

#### Primeiras impressões

Em um primeiro contato com o *python*, já me surpreendi muito a facilidade do mesmo, a sintaxe é clara as declarações, tanto que em muito as casos não é necessário sequer comentar, basta ler como um texto em Inglês.



Tablea de procedendia de calculo no python é igual a da matematica, segue ordem de procedendia.
> Dicas:  executar primeiro os parenteses focando sempre da esquerda para direita, use a mesma logica para os demais operadores

	1 - () # Parentes
		ex: 5 + (3 - 1) = 7
	2 - ** # Exponecial
		ex: 2 ** 3 = 8
	3 - % # Resto da divisão
		ex: 22 % 8 = 6
	4 - // # Divisão inteira
		ex: 22 // 8 = 2
	5 - / # Divisão
		ex: 22 / 8 = 2.75
	6 - * # Multiplicação
		ex: 3 * 5 = 15
	7 - - # Subtração
		ex: 5 - 2 = 3
	8 - + # Adição
		ex: 2 + 2 = 4

# alguns erros de sintax na operações
	5 +
	File "<stdin>", line x
	SyntaxError: invalid syntax

# Tipos de dados em python

No python existe basícamentes 4 tipos de dados

String (str) = texto
inteiro (int) = números inteiros
Float (flaot) = números reais
Boolean (bool) = True ou False

# Dica: em python em 90% do casos não é possivel, realizar operações entre string e operadores, porém existe um caso que funciona bem
	ex:
		"###"* 10
	stdout: ##############################

# Dica: para contatemas em python usa-se o "," ou "+" porém isto depende muito do caso, mas existe um saida para isto o "%s" ou meu favorito o ".format()"

	usando o ','
	ex:
		idade = 20 # tipo int
		print('Eu tenho ', idade)
		stdout: eu tenho 20

	Usando o +
	ex:
		nome = 'Santos' # tipo string
		print('Meu nome é José dos ' + nome)
		stdout: Meu nome é José dos Santos

	Usando o "%s"
	ex:
		nome = "Kaio Cesar"
		print('Meu nome é %s' % nome)

		stdout: Meu nome é Kaio Cesar


	Usando o format()
	ex:
		nome = "Kaio Cesar"
		idade = 25
		estado = MG

		print('Eu sou {}, tenho {} anos e moro no estado de {}'.format(nome, idade, estado))
		stdout: Eu sou Kaio Cesar, tenho 25 anos e moro no estado de MG
	comentario: Topzeraaa
'''
