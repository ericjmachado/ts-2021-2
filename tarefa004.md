## Tarefa 004 - 19/01/2022 - Análise do Valor Limte - Definição de casos de testes.

**DEFINIÇÃO**:

1. Considerando o conjunto de classes de equivalência que você definiu em atendimento à **Tarefa 003 - 21/12/2021 - Definição de Classes de Equivalência**.
2. Considerando as explicações a respeito do critério de teste funcional **Análise do Valor Limite** disponíveis em:
   1. [Análise do Valor Limite 1](https://viniciuspessoni.com/2020/03/15/analise-do-valor-limite/).
   2. [Análise do Valor Limite 2](https://www.youtube.com/watch?v=EQU5ODvmwzs).
   3. [Análise do Valor Limite 3](https://www.youtube.com/watch?v=jX7uyaTAn-k).
3. Pede-se a definição do conjunto de casos de testes necessários para o teste do mesmo cenário descrito na tarefa 003. Estes casos de teste deverão ser criadas a partir das diretrizes definidas pelo critério funcional "Análise do Valor Limte".
4. O Conjunto de casos de testes derivado deve seguir o seguinte padrão:

| CT   | Valor de Entrada                           | Resultado Esperado | Classe Equivalência |
| ---- | ------------------------------------------ | ------------------ | ------------------- |
| CT01 | quantidade de faltas = 26% da cargaHoraria | Valor Inválido     | CE1                 |
| CT02 | quantidade de faltas = -1% da cargaHoraria | Valor Inválido     | CE1                 |
| CT03 | media entre nota1 e nota2 = 4%             | Valor Inválido     | CE3                 |
| CT04 | media entre nota1 e nota2 = -1%            | Valor Inválido     | CE3                 |
| CT05 | media entre nota1 e nota2 = 6.0            | Valor Inválido     | CE5                 |
| CT06 | media entre nota1 e nota2 = 2.9            | Valor Inválido     | CE5                 |
| CT07 | media entre nota1 e nota2 = 6.1            | Valor Inválido     | CE7                 |
| CT08 | media entre nota1 e nota2 = 5.9            | Valor Inválido     | CE7                 |

Onde:
**CT** = Caso de Teste, seguido de um valor sequencial;
**Valor de entrada** é o valor informado para a variável;
**Resultado esperado** é o resultado que se espera da execução da função;
**Classe de Equivalência** é a identificação de qual classe de equivalência está sendo exercitada pelo caso de teste.
