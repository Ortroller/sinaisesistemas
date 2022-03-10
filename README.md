# Sinais e Sistemas
Trabalho Computacional de Sinais e Sistemas

## Objetivo

O objetivo deste trabalho é de permitir que o acadêmico implemente, por meio da utilização de uma ferramenta computacional:

* A decomposição de sinais em parte par e ímpar.
* As operações de rebatimento, multiplicação e soma que ocorrem em um somatório de convolução

## Detalhamento
### Decomposição de sinais
Implemente uma função que decomponha um sinal de tempo discreto X[n] em suas partes par Xp[n] e impar Xi[n]. A função deve apresentar a seguinte interface:

* Entrada:
````
– Sinal a ser decomposto x[n] (arranjo/vetor com os valores da variável dependente).
– Valor do tempo inicial de referência n0 (variável independente).
````

* Saída:
````
– Sinal par Xp[n] (arranjo/vetor com valores da variável dependente).
– Sinal impar Xi[n] (arranjo/vetor com valores da variável dependente).
– Valor do tempo inicial n0 (variável independente)
````

Realize testes com alguns sinais (escolha os sinais que julgar serem interessantes), apresentando sempre quatro gráficos:

* O sinal x[n]: n × x[n].
* A parte par Xp[n]: n × Xp[n].
* A parte impar Xi[n]: n × Xi[n].
* A soma entre as partes par e impar Xp[n] + Xi[n]: n × Xp[n] + Xi[n].



