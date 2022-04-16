<div align=center>
  <img src="brasaooficialcolorido.png">
</div>

#### <p style="text-align: center;">Universidade Federal de Goiás</p>
#### <p style="text-align: center;">Instituto de Informática</p>
#### <p style="text-align: center;">Bacharelado em Engenharia de Software</p>
#### <p style="text-align: center;">Teste de Software - 2021/2</p>
#### <p style="text-align: center;">Gilmar Ferreira Arantes</p>
####  <p style="text-align: center;"> Prova P2 - 12/04/2022</p>

Matrícula: 201703743

Nome: Cauã dos Santos Rebelo

<p><font color="red">Nota 5,98</font></p>


1. Quanto ao Processo de Teste de Software, responda as duas questões seguintes:
   1. (**0,5 ponto**) Defina os seguintes conceitos Processo de Teste de Software, Projeto de Teste de Software e Plano de Teste de Sofware.
O projeto seria a estrutura dos elementos de testes e a aplicação dos casos de teste, o processo é divido em estruturação de etapas, atividades, artefatos, papeis e responsabilidades que buscam a padronização dos trabalhos e melhorar a organização e controle dos projetos de testes.

<p><font color="red">Nota 0,3</font></p>

   2. (**0,5 ponto**) Descreva o relacionamento existente entre estes conceitos.

<p><font color="red">Nota 0,0</font></p>

2. (**1,0 pontos**) Descreva as vantagens para a equipe de desenvolvimento ao se adotar um processo de teste ágil.
O processo de teste ágil ocorre durante a fase do desenvolvimento frequentemente e com ciclos continuos, é feito por todos os membros da equipe, prioriza testes automatizados e em testes exploratórios. Ao adotar um processo de teste ágil, os testes são usados como complementação aos requisitos e a documentação do código, além de focar em testes de caixa preta e branca em todas as camadas da arquitetura.
<p><font color="red">Nota 1,0</font></p>

3. (**1,0 ponto**) Cite pelo menos três características do Teste Exploratório.
O teste exploratório é uma abordagem dos testes ágeis, tres caracteristicas unicas delas são: Pouco planejamento, maximo de execução, é um processo de teste iteravor e utiliza dados de testes feitos anteriomente para criar novos testes.
<p><font color="red">Nota 0,5</font></p>

4. Considere os arquivos .java (Banco.java, Agencia.java, Conta.java e BankValidator.java). Nos próprios arquivos .java estão definidas as regras para cadastramento de cada um deles (Banco, Agencia e Conta). Desta forma, pede-se:
   1. (2.0 Pontos) Definir os cenários de teste suficientes para testar o cadastro e movimentações financeiras envolvendo bancos, agências e contas, conforme especificado. Para cada cenário definir os critérios de teste adequados à definição dos seus casos de teste.

   **CT01:** Testar numero do Banco com 3 digitos

   **CT02:** Testar numero do Banco com menos que 3 digitos.

   **CT03:** Testar numero do Banco com mais de 3 digitos.

   **CT04:** Testar numero do Banco com caracterio invalido.

   **CT05:** Testar nome do Banco corretamente.

   **CT06:** Testar nome do Banco com menos de 3 digitos.

   **CT07:** Testar nome do Banco com mais de 100 digitos.

   **CT08:** Testar nome do Banco com caracter invalido.

   **CT09:** Testar numero da Agencia corretamente.

   **CT10:** Testar numero da Agencia com menos de 3 digitos.

   **CT11:** Testar numero da Agencia com mais de 5 digitos.

   **CT12:** Testar numero da Agencia com carcterio invalido.

   **CT13:** Testar nome da Agencia corretamente.

   **CT14:** Testar nome da Agencia com menos de 3 digitos.

   **CT15:** Testar nome da Agencia com mais de 100 digitos.

   **CT16:** Testar nome da Agencia com caracter invalido.

   **CT17:** Testar nome cidade da Agencia corretamente.

   **CT18:** Testar nome da cidade da Agencia com menos de 3 digitos.

   **CT19:** Testar nome cidade da Agencia com mais de 100 digitos.

   **CT20:** Testar nome cidade da Agencia com caracter invalido.

   **CT21:** Testar numero da Conta corretamente.

   **CT22:** Testar numero da Conta com numero de digitos diferente de 6.

   **CT23:** Testar numero da Conta com caracter invalido.

   **CT24:** Testar tipo da Conta corretamente.

   **CT25:** Testar tipo da Conta diferentemente de "corrente" ou "poupança".

   **CT26:** Testar o limite de uma Conta corrente.

   **CT27:** Testar o limite de uma Conta poupança incorretamente.

   **CT28:** Testar rendimento de uma Conta poupança.

   **CT29:** Testar rendimento de uma Conta corrente incorretamente.

   **CT30:** Testar debito de juros especial de uma Conta.

   **CT31:** Testar saque de uma Conta.

   **CT32:** Testar deposito de uma Conta.

   **CT33:** Testar transferencia entre uma Conta e outra.

   <p><font color="red">Nota 1,3</font></p>

   2. (2.0) Definir os casos de teste suficientes para a cobertura do teste de cada um dos cenários definidos. Documentar os casos de teste no seguinte padrão:
   |CT|Valores de Entrada|Resultado esperado|
   |---|---|---|
   |CT1|568, Banco UFG|568|
   |CT2|56, Banco UFG|NULL|
   |CT3|5687, Banco UFG|NULL|
   |CT4|56e, Banco UFG|NULL|
   |CT5|568, Banco UFG|Banco UFG|
   |CT6|568, Ba|NULL|
   |CT7|568, Banco UFGeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeee|NULL|
   |CT8|568, Banco UFG%$#!463|NULL|
   |CT9|6975, Universitario, Goiania, banco|6975|
   |CT10|69, Universitario, Goiania, banco|NULL|
   |CT11|6975756, Universitario, Goiania, banco|NULL|
   |CT12|69%5e, Universitario, Goiania, banco|NULL|
   |CT13|6975, Universitario, Goiania, banco|Universitario|
   |CT14|6975, Un, Goiania, banco|NULL|
   |CT15|6975, Universitarioeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeee, Goiania, banco|NULL|
   |CT16|6975, Univer@#%@#tario4141, Goiania, banco|NULL|
   |CT17|6975, Universitario, Goiania, banco|Goiania|
   |CT18|6975, Universitario, Go, banco|NULL|
   |CT19|6975, Universitario, Goianiaeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeee, banco|NULL|
   |CT20|6975, Universitario, Goian%#@#%#@!45, banco|NULL|
   |CT21|132478, Corrente, agencia|132478|
   |CT22|1324784, Corrente, agencia|NULL|
   |CT23|1324r8, Corrente, agencia|NULL|
   |CT24|132478, Corrente, agencia|Corrente|
   |CT25|132478, Rjrqw, agencia|NULL|
   |CT26|132478, Corrente, agencia|1000|
   |CT27|132478, Poupanca, agencia|0|
   |CT28|132478, Poupanca, agencia, 0.01|1000.01|
   |CT29|132478, Corrente, agencia, 0.01|2000|
   |CT30|132478, Corrente, agencia, 900|1100|
   |CT31|132478, Corrente, agencia, 500|1500|
   |CT32|132478, Corrente, agencia, 10|2010|
   |CT33|132478, Corrente, agencia, 987648, Poupanca, agencia, 500|1500, 1500|

<p><font color="red">Nota 1,5</font></p>

3. (3.0 Pontos) Implementar (na linguagem de programação java) as classes para o teste da criação dos objetos e das movimentações financeiras envolvendo bancos e agências e contas.

<p><font color="red">Nota 1,38</font></p>


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
