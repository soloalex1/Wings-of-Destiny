v0.0.4
- criei uma fun��o em Jogo pra adicionar um "Aperte Enter para continuar", j� que era muito texto de uma vez. O ideal seria chamar essa fun��o depois de cada fun��o principal do jogo.

- tamb�m comecei a mexer em algumas coisas da narrativa. a fun��o gameStart (ou algo assim, esqueci) j� tem uma descri��ozinha do ambiente and shit.

- tava testando o sistema de skills de cada classe, mas preciso tirar algum tempo pra pensar melhor. coloquei uma skill pra cada uma das classes s� como string mesmo, por enquanto.


v0.0.5

- vai tomar no cu

- criei a classe Dado pra rolar os valores da batalha and shit.

- movi a fun��o de setar o nome do jogador pra classe Jogador (o que � estranho porque j� deveria estar l�).


v0.0.6

- tratamento de erros na inser��o do nome (ainda com alguns bugs, mas j� d� pra ter uma ideia)

- m�todo ataqueUm da classe abstrata mudado de void pra int(pra retornar o dano do ataque, essas coisas a�)

- dei uma mexida b�sica beeeeem por cima na parte da batalha, mas preciso parar pra fazer direito


v0.0.7

- batalha quase totalmente implementada :D

- adicionadas duas Strings ataqueUm e ataqueEspecial pra reutilizar o nome das skills ao longo do c�digo (�til pra batalha funcionar pra todas as classes and shit)

- coloquei os ataques especiais e setei somaDano pra ser o adicional de dano na rolagem

v0.0.8

- deu certo a batalha hehehehehehe
	- exibe o custo de mana do lado das habilidades
	- rola o dado de acordo com o atributo (s� o cl�rigo, lembrar de mexer no resto)
	- falta colocar algo na morte e mostrar o invent�rio

v0.0.9

- reconfigura��o da classe Dado para adaptar ao padr�o Singleton
- atributos de combate implementados em todas as classes
- ajustes de encapsulamento dos m�todos das classes Jogo e Jogador
- primeiros testes com a interface MonstroNew e o padr�o Decorator


v0.1.0

- ajustes de interatividade nas classes do personagem
- remo��o da classe Personagem (por ser desnecess�ria)
- abandono dos testes do Decorator para os monstros
- criada a superclasse Monstro e uma subclasse Goblin
- ajustes na rolagem do dado e na batalha (texto mais objetivo, maior retorno para o usu�rio)

v0.1.1

- in�cio da implementa��o da narrativa
- ajustes na interatividade com a fun��o Jogo.teclaSistema()
- ajustes nos di�logos na escolha de classe
- implementada classe Orc para testes futuros


v0.1.2

- continua��o da narrativa
- desistindo do decorator nos monstros e come�ando a implementar os itens
- poss�vel ado��o do padr�o Strategy

v0.2

- implementa��o do padr�o Factory na cria��o e inicializa��o dos itens
- implementado um m�todo para exibir os status a qualquer momento na classe jogador
- invent�rio implementado

v0.2.1

- implementa��o de m�todos para consumo de itens atrav�s do invent�rio (fora de combate)
- consumo de itens dentro de combate ainda em desenvolvimento
- corre��es menores