<div align=center>
  <img src="brasaooficialcolorido.png">
</div>

#### <p style="text-align: center;">Universidade Federal de Goiás</p>
#### <p style="text-align: center;">Instituto de Informática</p>
#### <p style="text-align: center;">Bacharelado em Engenharia de Software</p>
#### <p style="text-align: center;">Teste de Software - 2021/2</p>
#### <p style="text-align: center;">Gilmar Ferreira Arantes</p>
####  <p style="text-align: center;"> Prova P1 - 16/02/2022</p>

Matrícula: 201703749 <br>
Nome: Eric de Jesus Machado

<p><font color=red>Nota: 2,7.</font></p>

1. Quanto ao objetivo do Teste de Software, responda as duas questões seguintes:
   1. (**0,5 ponto**) Qual o objetivo primário da atividade de teste de software?<br>
   R: avaliar a qualidade da aplicação e reduzir o risco de falha em operação. <font color=red>Errado.</font>

   2. (**0,5 ponto**) O que acontece, quando não se atinge este objetivo primário? <br>
   R: Deve se realizar a gestão de defeitos, afim de corrigir as falhas de software. <font color=red>Errado.</font>


2. (**1,0 ponto**) Explique o que é o teste exaustivo e porque sua execução não é possível. <br>
R: Um teste onde todas as possibilidades são testadas, ou seja, eu testo todos os possíveis dados de entrada, é impossivel pois são muito custosos e demandariam muito tempo. É praticamente impossível testar todas as possibilidades de entrada e saída de um software, a não ser que seja muito simples. <font color=green>Certo.</font>

3. (**1,0 ponto**) Cite pelo menos duas limitações da Técnica de Teste Funcional e duas da Técnica de Teste Estrutural. <br>
R: A limitação do teste funcional, se da pelo custo e o tempo de executar os testes, necessita de uma equipe especializada para criar os testes.
Já a desvantagem do teste estrutural e que necessita de uma vasta cobertura de código, o que demanda muito tempo da equipe de desenvolvimento, outra desvantagem e que deve ser feito por outro desenvolvedor que não fez o código, poís isso pode viciar o teste. <font color=red>Errado.</font>

4. (**1,0 ponto**) Descreva pelo menos um dos quatro níveis de teste constantes da literatura especializada. <br>
R: Teste unitário consiste onde toda a aplicação de teste nas assinaturas de entrada e saída de um sistema. <font color=red>Errado.</font>

5. (**1.0 ponto**)Descreva qual o propósito do critério de teste funcional Particionamento por Classes de Equivlência.<br>
R: Ele tem por objetivo minimizar o número de casos de teste, selecionando apenas um caso de teste de cada classe, pois em princípio todos os elementos de uma classe devem se comportar de maneira equivalente. <font color=orange>Parcialmente correto. Nota 0,7.</font>

6. (**1.00 ponto**) Existe algum tipo de hierarquia em relação aos critérios de teste estrutural, todos os nós, todos os arcos e todos os caminhos? Se sim, explique-a, considerando a perspectiva dos níveis de cobertura desejados.
R: Sim
* Nivel 0: Menos de 100% cobertura sobre os nós
* Nível 1: Teste em todos os nós
* Nível 2: Teste todos os arcos
* Nível 3: Cobertura de todas as condicoes.
* Nível 4: Cobertura de decisões e condições.
* Nível 5: Cobertura de condições multíplas.
* Nível 6: Cobertura dos caminhos.

<font color=green>Certo.</font>


7. Considere a especificação, a seguir, de um hipotético programa que objtiva a classificação de um triângulo, a partir dos valores informados para os seus três lados.

   a) Dado um triângulo cujos segmentos medem A, B e C, que são números inteiros positivos na faixa de 0 a 100. Esse triângulo somente existirá se: (A + B < C) ou (A + C < B) ou (B + C < A).
   b) Quanto às medidas dos seus lados o triângulo, poderá ser classicado em:
         • Isósceles = quando possui dois lados com a mesma medida;
         • Escaleno = quando todos os seus lados têm medidas diferentes;
         • Equilátero = quando todos os lados tem a mesma medida;
         • Acutângulo = quando o quadrado de um dos seus lados é menor que a soma do quadrado dois outros dois. (A<sup>2</sup> < B<sup>2</sup> + C<sup>2</sup>).
         • Retângulo: quando o quadrado de um dos seus lados é igual à soma do quadrado dois outros dois. (A<sup>2</sup> = B<sup>2</sup> + C<sup>2</sup>).
         • Obtusângulo: quando o quadrado de um dos seus lados é maior que a soma do quadrado dois outros dois. A<sup>2</sup> > B<sup>2</sup> + C<sup>2</sup>.

7.1 (**2.0 pontos**) Definir uma tabela de decisão para o teste tanto da existência do triângulo, quanto para a definição do seu tipo. Consulte exemplo de tabela de decisão na tarefa 005.

<font color=red>Questão não respondida.</font>

7.2 (**2.0 pontos**) Criar os conjunto de casos de teste necessários para a cobertura das combinações constantes da tabela de decisão, seguindo o seguinte padrão:
|CT|Lado A|Lado B|Lado C|Resultado|
|---|---|---|---|---|
|   |   |   |   |   |

<font color=red>Questão não respondida.</font>

INSTRUÇÕES:
1. Tipo: Prova individual;
2. Local de Entrega: Plataforma Turing
3. Forma de Entrega: Entregar este arquivo, editado com suas respostas, no formato .md, nominado da seguinte forma: ts2021-2_prova-p1_mat.md, onde mat deverá ser substituído pelo número da sua matrícula.
4. **Entrega diferente da especificada não será avaliada.**
5. Data da Entrega: 22/02/2022, as 23h59min.
6. Critério de Aceitação: arquivo entregue, conforme solicitado.
