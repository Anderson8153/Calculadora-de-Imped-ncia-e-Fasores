# Calculadora de Impedância e Fasores

Calculadora web para circuitos de corrente alternada em regime senoidal permanente. Resolve reatâncias, Lei de Ohm e associações em série ou paralelo de resistores, indutores e capacitores, mostrando o **passo a passo** de cada conta e o **diagrama fasorial**.

**Acesse online:** (https://anderson8153.github.io/Calculadora-de-Imped-ncia-e-Fasores/)

## O que ela faz

- **Exercício por etapas:** mostra uma etapa por vez (dados, impedância de cada elemento, impedância equivalente, corrente total, tensões e correntes por elemento, diagrama fasorial).
- **Exercício de uma só vez:** o mesmo circuito, com resultado final e todas as etapas listadas juntas.
- **Ferramenta de componentes:** calcula Z<sub>R</sub>, Z<sub>L</sub> e Z<sub>C</sub> a partir de R, L, C e da frequência.
- **Ferramenta da Lei de Ohm:** descobre Z, I ou V a partir dos outros dois, em forma polar (módulo ∠ ângulo) ou retangular (a + jb).

Cada resultado traz o teor do circuito (indutivo, capacitivo ou resistivo), o triângulo de impedâncias, as expressões no domínio do tempo, como `v(t) = 220·√2·sen(377·t + 0°)`, e um diagrama fasorial em escala normalizada.

## Fórmulas utilizadas

| Grandeza | Fórmula |
|---|---|
| Reatância indutiva | X<sub>L</sub> = 2·π·f·L ∠ +90° |
| Reatância capacitiva | X<sub>C</sub> = 1 / (2·π·f·C) ∠ −90° |
| Lei de Ohm | V = Z · I |
| Série | Z<sub>eq</sub> = Z<sub>1</sub> + Z<sub>2</sub> + … + Z<sub>n</sub> |
| Paralelo | 1/Z<sub>eq</sub> = 1/Z<sub>1</sub> + 1/Z<sub>2</sub> + … + 1/Z<sub>n</sub> |

## Exemplo incluído

A página abre com um exercício resolvido: fonte de 220 V ∠ 0° a 60 Hz alimentando, em série, um indutor de 100 mH, capacitores de 20 mF e 30 mF e um resistor de 1 kΩ.

| Resultado | Valor |
|---|---|
| X<sub>L</sub> | 37,699 ∠ +90° Ω |
| Z<sub>eq</sub> | 1.000,70 ∠ +2,146° Ω (teor indutivo) |
| i | 0,2198 ∠ −2,146° A |

## Como usar

1. Informe a frequência no canto superior direito, em Hz ou rad/s.
2. Monte o circuito adicionando elementos (R, L, C ou uma impedância qualquer) e escolha série ou paralelo.
3. Ative a fonte de tensão para obter a corrente total e os valores por elemento.
4. Para circuitos mistos, resolva por partes: calcule uma associação, clique em **Levar Zeq para uma nova associação** e combine com o restante.

