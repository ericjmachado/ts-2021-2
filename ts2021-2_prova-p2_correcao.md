<div align=center>
  <img src="brasaooficialcolorido.png">
</div>

#### <p style="text-align: center;">Universidade Federal de Goiás</p>
#### <p style="text-align: center;">Instituto de Informática</p>
#### <p style="text-align: center;">Bacharelado em Engenharia de Software</p>
#### <p style="text-align: center;">Teste de Software - 2021/2</p>
#### <p style="text-align: center;">Gilmar Ferreira Arantes</p>
####  <p style="text-align: center;"> Prova P2 - 12/04/2022</p>

Matrícula: 201703749

Nome: Eric de jesus machado

<p><font color="green">Nota 6,13</font></p>


1. Quanto ao Processo de Teste de Software, responda as duas questões seguintes:
   1. (**0,5 ponto**) Defina os seguintes conceitos Processo de Teste de Software, Projeto de Teste de Software e Plano de Teste de Sofware. <br />
   R: O projeto descreve a estrutura dos elementos de testes e a realização dos casos de teste, já o processo e divido em estruturação de etapas, atividades, artefatos, papéis e responsabilidades que buscam a padronização dos trabalhos e ampliar a organização e controle dos projetos de testes.
   O plano de teste consiste numa modelagem detalhada do fluxo de trabalho durante o processo.
      <p><font color="red">Nota 0,5</font></p>

   2. (**0,5 ponto**) Descreva o relacionamento existente entre estes conceitos.<br />
   R: Dentro do ciclo de vida de teste, o projeto de teste consiste na etapa de planejamento, implantação e execução dos processos da garantia de qualidade, já o plano de testes será executado como parte do projeto que estará seguindo os processos que foram definidos e seus resultados esperados para que possa ser medida a eficácia dos testes.
      <p><font color="red">Nota 0,5</font></p>

2. (**1,0 pontos**) Descreva as vantagens para a equipe de desenvolvimento ao se adotar um processo de teste ágil.<br />
   R: Em uma metodologia ágil de teste, os testes ocorrem durante o desenvolvimento em ciclos frequentes e continuos, possuem maior foco em testes exploratórios, são usados como complementação de requisitos e como documentação de código. São realizados com maior foco por meio automatizado e podem ser realizadas por qualquer um da equipe.
   <p><font color="red">Nota 0,7</font></p>


3. (**1,0 ponto**) Cite pelo menos três caractereísticas do Teste Exploratório.
<br />
R: O teste exploratório é uma abordagem de teste ágil, algumas de suas caractereísticas são, mínimo de planejamento e máximo de execução, é um processo de teste iterativo, e por fim ele utiliza de dados de testes anteriores para desenvolver novos e melhores testes.
    <p><font color="red">Nota 1,0</font></p>

4. Considere os arquivos .java (Banco.java, Agencia.java, Conta.java e BankValidator.java). Nos próprios arquivos .java estão definidas as regras para cadastramento de cada um deles (Banco, Agencia e Conta). Desta forma, pede-se:
   1. (2.0 Pontos) Definir os cenários de teste suficientes para testar o cadastro e movimentações financeiras envolvendo bancos, agências e contas, conforme especificado. Para cada cenário definir os critérios de teste adequados à definição dos seus casos de teste. <br />



   **CT01:** Testar número do Banco com menos que 3 dígitos.

   **CT02:** Testar número do Banco com mais de 3 dígitos.

   **CT03:** Testar número do Banco negativo.

   **CT04:** Testar número do Banco válido.

   **CT05:** Testar nome do Banco com menos de 3 dígitos.

   **CT06:** Testar nome do Banco com mais de 100 dígitos.

   **CT07:** Testar nome do Banco com caractere inválido.

   **CT08:** Testar nome do Banco corretamente.

   **CT09:** Testar número da Agencia com menos de 3 dígitos.

   **CT10:** Testar número da Agencia com mais de 5 dígitos.

   **CT11:** Testar número da Agencia corretamente.

   **CT12:** Testar nome da Agencia com menos de 5 dígitos.

   **CT13:** Testar nome da Agencia com mais de 100 dígitos.

   **CT14:** Testar nome da Agencia com caractere inválido.

   **CT15:** Testar nome da Agencia corretamente.

   **CT16:** Testar nome da cidade com menos de 5 dígitos.

   **CT17:** Testar nome da cidade com mais de 100 dígitos.

   **CT18:** Testar nome da cidade com caractere inválido.

   **CT19:** Testar nome da cidade corretamente.

   **CT20:** Testar número da Conta com número de dígitos diferente de 6.

   **CT21:** Testar número da Conta corretamente.

   **CT22:** Testar tipo da Conta diferentemente de "corrente" ou "poupança".

   **CT23:** Testar tipo da Conta corretamente.

   **CT24:** Testar o limite de uma Conta corrente.

   **CT25:** Testar o limite de uma Conta poupança incorretamente.

   **CT26:** Testar saque de uma Conta.

   **CT27:** Testar deposito de uma Conta.

   **CT28:** Testar transferencia entre uma Conta e outra.
   <p><font color="red">Nota 1,0</font></p>

   2. (2.0) Definir os casos de teste suficientes para a cobertura do teste de cada um dos cenários definidos. Documentar os casos de teste no seguinte padrão:

   CT | Valores de Entrada|Resultado esperado|
   --------- | ------ | ------
   CT01 | 12| NULL
   CT02 | 1244| NULL
   CT03 | -325| NULL
   CT04 | 325| 325
   CT05 | Ban| NULL
   CT06 | Ban * 50| NULL
   CT07 | Bom banco 25| NULL
   CT08 | Banco dos sonhos| Banco dos sonhos
   CT09 | 12| NULL
   CT10 | 123456| NULL
   CT11 | 325| 325
   CT12 | Ag| NULL
   CT13 | Ag * 100| NULL
   CT14 | Agencia 23| NULL
   CT15 | Agencia| Agencia
   CT16 | Goia| NULL
   CT17 | Goiania * 50| NULL
   CT18 | Goiania5| NULL
   CT19 | Goiania| Goiania
   CT20 | 1234567| NULL
   CT21 | 123456| 123456
   CT22 | Corrent| NULL
   CT23 | Corrente| Corrente
   CT24 | Corrente| 10000.0
   CT25 | Poupanca| NULL
   CT26 | 1000.0| 19000.0
   CT27 | 1000.0| 21000.0
   CT28 | 1000.0| 21000.0

   <p><font color="red">Nota 1,0</font></p>

   3. (3.0 Pontos) Implementar (na linguagem de programação java) as classes para o teste da criação dos objetos e das movimentações financeiras envolvendo bancos e agências e contas.

<p><font color="red">Nota 1,43</font></p>

INSTRUÇÕES:
1. Tipo: Prova individual;
2. Local de Entrega: Plataforma Turing.
3. Forma de Entrega: arquivo compactado contendo:
   1. Este arquivo md, respondido.
   2. Classes de teste para (BancoTest, AgenciaTest e ContaTest);
   3. O arquivo compactado deverá ter o seguinte nome prova_p2<mat>.zip, onde mat é o número da matrícula do aluno(a).
5. Data da Entrega: 12/04/2022, as 22hs.
6. Critério de Aceitação: arquivo entregue, conforme solicitado.
7. Obs: segue no mesmo pacote o arquivo "org.apache.commons.lang.StringUtils", que é uma dependência do projeto. É deve ser inserida no _classpath_ do projeto de implementação da questão 4, caso não esteja utilizando o _maven_.
