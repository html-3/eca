---
title: Sistemas Digitais - P1 Gabarito
---
## Questão 1
### a) Determine a tensão $V$ e a corrente $I$ do seguinte circuito

A tensão nominal do diodo informa que o nó $A$ tem a seguinte tensão caso corrente esteja passando por ele.
$$
V_A = 0,7 V
$$
A tensão $V$ pode ser calculada pela lógica anterior. Assim $V = 0 V$

A partir isso, pode-se estivar a corrente pela lei de Ohm.
$$
R \overset{\Delta}{=} \frac{V}{I} 
$$

Corrente passando pelo primeiro resistor.
$$
I_0 = \frac{3 - 0,7}{6 \cdot 10^6} \approx 0,38 \mu A
$$

Corrente passando pelo segundo resistor.
$$
I_2 = \frac{0 - (-3)}{12 \cdot 10^6} = 0,25 \mu A
$$

Pela lei de Kirchhoff para Correntes podemos dizer que:
$$
\sum_{i=0}^(N)I_i=0
$$

$$
I_0 - I - I_2 = 0 \\
0,38 - I - 0,25 = 0 \\
I = 0,25 - 0,38 = -0,13 \mu A
$$

Este resultado é impossível porque o diodo ideal não permite corrente em seu sentido inverso. Assim, a dedução que corrente passa pelo diodo ligado ao terra leva a conclusões equivocadas. 
$$
I = 0 A \implies V_A = 0 V \implies V = -0,7V
$$

### b) Determine a tensão $V$ e a corrente $I$ do seguinte circuito
Identico ao circuito anterior, assumimos que corrente passa pelo primeiro diodo.
$$
V_A = 0,7 V \implies V = 0V
$$

Corrente passando pelo primeiro resistor.
$$
I_0 = \frac{3 - 0,7}{12 \cdot 10^6} \approx 0,19 \mu A
$$

Corrente passando pelo segundo resistor.
$$
I_2 = \frac{0 - (-3)}{6 \cdot 10^6} = 0,50 \mu A
$$

Pela lei de Kirchhoff para Correntes podemos dizer que:
$$
\sum_{i=0}^(N)I_i=0
$$

$$
I_0 - I - I_2 = 0 \\
0,19 - I - 0,50 = 0 \\
I = 0,50 - 0,19 = 0,31 \mu A
$$

## Questão 2
Desenvolva uma ALU de entrada serial com soma, substração, inversão e complemento de dois.

## Questão 3

## Questão 4
