# Sinais e Sistemas
Trabalho Computacional de Sinais e Sistemas

## Objetivo

O objetivo deste trabalho é de permitir que o acadêmico implemente, por meio da utilização de uma ferramenta computacional:

* A decomposição de sinais em parte par e ímpar.
* As operações de rebatimento, multiplicação e soma que ocorrem em um somatório de convolução

## Detalhamento
### Decomposição de sinais
Implemente uma função que decomponha um sinal de tempo discreto $ X[n]$ em suas partes par $X_p[n]$ e impar $X_i[n]$. A função deve apresentar a seguinte interface:

* Entrada:

> Sinal a ser decomposto $ X[n]$ (arranjo/vetor com os valores da variável dependente).

> Valor do tempo inicial de referência $n_0$ (variável independente).


* Saída:

> Sinal par $X_p[n]$ (arranjo/vetor com valores da variável dependente).

> Sinal impar $X_i[n]$ (arranjo/vetor com valores da variável dependente).

> Valor do tempo inicial $n_0$ (variável independente)


Realize testes com alguns sinais (escolha os sinais que julgar serem interessantes), apresentando sempre quatro gráficos:

* O sinal $X[n]: n × X[n]$.
* A parte par $X_p[n]: n × X_p[n]$.
* A parte impar $X_i[n]: n × X_i[n]$.
* A soma entre as partes par e impar $X_p[n] + X_i[n]: n × X_p[n] + X_i[n]$.

### Soma de Convolução

Implemente uma função que realize a convolução entre dois sinais de tempo discreto $x[n]$ e $h[n]$. A função deve apresentar a seguinte interface:
* Entrada:

> Sinal $x[n]$ (arranjo/vetor com os valores da variável dependente).
> Sinal $h[n]$ (arranjo/vetor com os valores da variável dependente).
> Valor do tempo inicial de referência $n_0$ (variável independente).


* Saída: 

> Sinal par $y[n]$ (arranjo/vetor com valores da variável dependente).
> Valor do tempo inicial $n_0$ (variável independente).

Realize testes com alguns sinais (escolha os sinais que julgar serem interessantes), apresentando sempre quatro gráficos:

* O sinal $x[n]: n × x[n]$.
* O sinal $h[n]: n × h[n]$.
* O sinal $y[n]: n × y[n]$.





