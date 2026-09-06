VEJA EM CODIGO! , PRE VISUALIZACAO TA UM C*

obs : "  " = Mensagens minhas, Não implementaveis no programa

- IMPLEMENTAÇÃO DO NOME DO JOGADOR(OPCIONAL) -

nome = ('diga seu nome...')
print(nome)

- ESCOLHA ALEATORIA DA MAQUINA -

import random                                " este 'import random' , deixe nas primeiras linhas. Nao precisa colocalo junto ao codigo "
opcoes = ['pedra', 'papel, 'tesoura']
escolha = random.choice(opcoes)

- JOGADOR ESCOLHE -

jogador = input('escolha entre pedra, papel ou tesoura:").strip() - " Tenho um serio problema em sempre dar espaço em respostas input kkkk, mas é completamente opcional " e .lower() - Sempre transfomar em minusculas( no meu caso as respostas sempre serão minusculas. )

- RESULTADO -

EMPATE:

if escolha "nome da variavel escolhido da maquina" == jogador "nome da variavel da escolha do jogador"
 " programa dirá que deu empate "

JOGADOR GANHA:

" Minha formula foi destribuilos em varios "elif" em situações onde o jogador ganha . Aplicando tambem o "and" para combinar as condições e der o retorno 'true' "

exemplo:

elif jogador == 'pedra' and escolha == 'tesoura'
 " programa dira que você ganhou "

MAQUINA GANHA:

" mesma coisa da formula acima , mas agora a maquina ganha "

elif jogador == 'pedra' and escolha == 'papel'
 " programa dira que você perdeu " 

- EXTRA - JOGAR NOVAMENTE OU ENCERRAR O PROGRAMA E CONTAGEM REGRESSIVA -

JOGAR MAIS UMA VEZ:

" quis dar a opção do jogador querer desafiar a maquina mais uma vez, assim fazendo um loop "

obs : para o loop funcionar,  o 'while True' precisa ser ativado onde voçê quer que o jogo comece novamente e terminar onde voçê quer que acabe com o 'break' ; No meu caso, o comeco foi depois do programa perguntar meu nome.

obs : todas as linhas de codigo precisam estar dentro do 'while True', caso não, o loop não funcionara! ( use o 'Tab' do teclado para alinhar as linhas do codigo ) " isso me deu uma dor de cabeça kkkkkk "

resposta = input('quer jogar novamente? (sim/nao)').strip().lower()
 if resposta == nao
  print('desligando programa')
  break
  " programa encerra com o 'break', e caso queira jogar denovo e só ativar o codigo mais uma vez "
  
 else:
     print('reiniciando o programa')
    " programa volta para onde o 'while True' foi implementado "

CONTAGEM REGRESSIVA:

" bem simples, so implementei para dar um charme"

obs: implemente a funcão 'import time' laaaaa no comeco do codigo , bem na primeira linha. Caso não implemente o 'time,.sleep(1)' nao funcionara e a contagem saira de uma so vez.

for contagem in range(3, 0, -1):
  print(contagem)
  time.sleep(1) 

obs: coloque este codigo apos o programa perguntar se quer 'jogar novamente'

exemplo: input('jogar mais uma vez')    →   print('mensagens')    →   contagem regressiva

" Espero que esteja tudo aqui"

" parece facil, e é facil kkkk , mas levou um tempinho pro jumento pensar em tudo "

" desculpa pelos erros ortograficos ; nem ferrando que vou ajustar isso kkkkk "



















OUÇA BK E BEBA ÁGUA ♡ 
