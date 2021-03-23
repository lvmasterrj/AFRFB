# Raciocínio Lógico-Quantitativo

## Log
17.03.21 - Aula Demonstrativa - (Introdução à Lógica de Argumentação) - QUESTÕES COMENTADAS PELO PROFESSOR (11)
19.03.21 - Lógica de Argumentação - Equivalência Entre Proposições

## Edital 2014

- [ ] 1. Estruturas Lógicas.
- [ ] 2. Lógica de Argumentação. 
- [ ] 3. Diagramas Lógicos.
- [ ] 4. Trigonometria.
- [ ] 5. Matrizes, Determinantes e Solução de Sistemas Lineares.
- [ ] 6. Álgebra.
- [ ] 7. Combinações, Arranjos e Permutação.
- [ ] 8. Probabilidade, Variáveis Aleatórias, Principais Distribuições de Probabilidade, Estatística Descritiva, Amostragem, Teste de Hipóteses e Análise de Regressão.
- [ ] 9. Geometria Básica.
- [ ] 10. Juros Simples e Compostos, Taxas de Juros, Desconto, Equivalência de Capitais, Anuidades e Sistemas de Amortização.
- [ ] 11. Compreensão e elaboração da lógica das situações por meio de: raciocínio matemático (que envolvam, entre outros, conjuntos numéricos racionais e reais - operações, propriedades, problemas envolvendo as quatro operações nas formas fracionária e decimal; conjuntos numéricos complexos; números e grandezas proporcionais; razão e proporção; divisão proporcional; regra de três simples e composta; porcentagem); raciocínio sequencial; orientação espacial e temporal; formação de conceitos; discriminação de elementos. 

## Anotações

### Lógica de Argumentação

#### - Proposição lógica
_Ou lógica bivalente (Verdadeiro ou Falso)_
```
1) É uma oração
2) É declarativa
3) Pode ser classificada como Verdadeira ou Falsa
```

**_Não são Proposições:_**
```
- Perguntas
- Exclamações
- Ordens
- Sentenças abertas
- Paradoxos
- Frases sem verbo
```

Atende aos seguintes Princípios:
- Princípio da não-contradição
- Princípio da exclusão do terceiro termo
- Princípio da identidade

#### - Operadores Lógicos

**- Operador de Conjunção "E"**

> P e Q | `P ^ Q`
_a conjunção só é V quando todas as suas componentes são V_

 | P   | Q   | P^Q |
 | --- | --- | --- |
 | V   | V   | V   |
 | V   | F   | F   |
 | F   | V   | F   |
 | F   | F   | F   |

Negação: ~P ou ~Q / `~P v ~Q`

**- Operador de Disjunção simples ou inclusiva "OU"**

> P ou Q | P v Q
_a disjunção só é F quando TODAS as proposições são F_

 | P   | Q   | P^Q |
 | --- | --- | --- |
 | V   | V   | V   |
 | V   | F   | V   |
 | F   | V   | V   |
 | F   | F   | F   |

Negação: ~P e ~Q / `~P ^ ~Q`

**- Operador Condicional (“SE..., ENTÃO ...”)**

> se P então Q | `P --> Q`
_só é F quando a condição "P" é V e, mesmo assim, o resultado "Q" é F_

 | P   | Q   | P^Q |
 | --- | --- | --- |
 | V   | V   | V   |
 | V   | F   | F   |
 | F   | V   | V   |
 | F   | F   | V   |

Negação: P e ~Q / `P ^ ~Q`
_***MANÉ**, de **MA**ntém a primeira e **NE**ga a segunda_

**- Operador Bicondicional (“SE E SOMENTE SE”)**

> P se e somente se Q | `P <=> Q`
_só é V quando as proposições têm valores lógicos iguais_

 | P   | Q   | P^Q |
 | --- | --- | --- |
 | V   | V   | V   |
 | V   | F   | F   |
 | F   | V   | F   |
 | F   | F   | V   |

Negação: ou P ou Q / P &#8891; Q ou `P <=> ~Q` ou `~P <=> Q`

**- Operador Disjunção Exclusiva (“OU... OU...”)**

> ou P ou Q | P &#8891; Q
_só é V quando as proposições têm valores lógicos Opostos_

 | P   | Q   | P^Q |
 | --- | --- | --- |
 | V   | V   | F   |
 | V   | F   | V   |
 | F   | V   | V   |
 | F   | F   | F   |

Negação: P se e somente se Q / `P <=> Q`

**Resumo**
| Proposição                      | Quando é falsa                     |
| ------------------------------- | ---------------------------------- |
| Conjunção (p e q)               | Alguma proposição é F              |
| Disjunção (p ou q)              | Todas as proposições são F         |
| Condicional (p --> q)           | V --> F  (Vera Fischer)            |
| Bicondicional (p<=>q)           | Proposições têm valores diferentes |
| Disjunção exclusiva (ou p ou q) | Proposições têm valores iguais     |

#### - Terminologia
**Tautologia**: uma proposição que é SEMPRE verdadeira.
**Contradição**: uma proposição que é SEMPRE falsa.
**Contingência**: uma proposição que pode assumir valores lógicos V e F, conforme o caso.

#### - Proposições Equivalentes

`P --> Q` = `~Q --> ~P` = `~P ou Q`

`~Q --> ~P` (CONTRAPOSITIVA da proposição condicional.)


##### - Equivalência da bicondicional

`P<=>Q` = `(P-->Q)^(Q-->P)`

_Estudo se e somente se trabalho = Se estudo, então trabalho e, se trabalho, então estudo_

##### -  Equivalência da disjunção exclusiva:

`P ⊻ Q` = `P<=>~Q` ou `~P<=>Q`

_Ou estudo ou trabalho = Estudo se e somente se NÃO trabalho = NÃO estudo se e somente se trabalho_