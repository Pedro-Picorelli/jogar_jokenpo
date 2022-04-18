'''Exercício Python 45: Crie um programa que faça o computador jogar Jokenpô com você.'''

from random import choice

x = [1, 2, 3]
x = choice(x)

if x == 1:
    resultx = 'PEDRA'
elif x == 2:
    resultx = 'PAPEL'
elif x == 3:
    resultx = 'TESOURA'

escolha = int(input("""SUAS OPÇÕES
[1] PEDRA
[2] PAPEL
[3] TESOURA 
QUAL SUA ESCOLHA: """))

if escolha == 1:
        result = 'PEDRA'
        if x == 1:
            resultado = 'EMPATOU'
        elif x == 2:
            resultado = 'PEDEU'
        elif x == 3:
            resultado = 'GANHOU'


elif escolha == 2:
        result = 'PAPEL'
        if x == 1:
            resultado = 'GANHOU'
        elif x == 2:
            resultado = 'EMPATOU'
        elif x == 3:
            resultado = 'PERDEU'

elif escolha == 3:
        result = 'TESOURA'
        if x == 1:
            resultado = 'PERDEU'
        elif x == 2:
            resultado = 'GANHOU'
        elif x == 3:
            resultado = 'EMPATOU'

if 1 <= escolha <= 3:
    print('''{} vs {}
    {}'''.format(result, resultx, resultado))

else:
     print('OPÇÃO INVALIDA')

