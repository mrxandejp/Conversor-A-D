# Conversor A/D: medição de tensão e indicação em % de 5V

## Objetivo:
Exercício de familiarização com o conversor A/D do PIC e desenvolvimento de rotinas aritméticas.

## Especificações:
* A conversão A/D foi feita em 8 bits pela porta GP2;
* A aquisição de 32 valores para calcular a média de cada medida;
* A conversão A/D foi efetuada, em modo cíclico e tão rápido quanto possível (limitado pela
velocidade do microcontrolador);
* O valor da média conversão A/D foi transformado para o correspondente percentual de tensão,
com 100% correspondendo a 5V;
* O valor do percentual da tensão, em notação de base decimal, é visualizado no display LCD;
* O valor mostrado no display é atualizado a cada 200 ms;
* Foi feito reuso das suas rotinas desenvolvidas na atividade 2/Av2 para indicação no LCD;
* Veja alguns exemplos:

    | Tensão medida (V)| Valor mostrado no display|
    | ------------- |:-------------:| 
    |   0.4         | 8%            |
    |   1.8         | 36%           |
    |   2.7         | 54%           |
    |   4.5         | 90%           |
    |   5.0         | 100%          |
