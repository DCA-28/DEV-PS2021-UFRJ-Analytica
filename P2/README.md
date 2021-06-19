# Comentários das ideais utilizadas em cada programa

## Q1

No primeiro problema de programação as observações principais foram, verificar se a entrada consistia de um número inteiro
e tratar o caso de uma possível divisão por zero quando nenhum número é inserido.

## Q2

No segundo problema, para criar uma solução otimizada, a ideia geral consiste em, a partir da posição inicial do cavalo,
usar os pares de números em 'operators' para simular todos os possíveis movimentos realizados por este. E, após isso, verificar
quais posições realmente eram válida (estavam dentro do tabuleiro). Por último, usei a biblioteca pandas para simular o tabuleiro,
indicando o cavalo ('h') e as possíveis posições para as quais ele pode se movimentar.

## Q3

Aqui achei válida a implementação do conceito de programação orientada a objetos para criar um objeto 'caixa eletrônico'. Durante a
execução do programa criamos um 'caixa eletrônico'. Na definição desse objeto, foram criadas funções para calcular as notas e moedas
que devem ser retornadas ao usuário (função 'withdraw'), e para realizar o retorno em si dessas notas e moedas (função 'cash_returned').

## Q4

No último programa, temos que todas as linhas do arquivo são lidas de uma vez e armazenadas na variável 'lines'. Depois percorremos cada
uma dessas linhas, separando suas palavras com 'split()' e verificando se estas já tinham sido descobertas ou não, ao compararmos tais palavras com as
chaves do dicionário que está realizando o armazenamento das mesmas. Criei a função 'verify_special_char' para verificar se o último caractere
de cada palavra era realmente uma letra e não um símbolo como ',' '?' '!'.
