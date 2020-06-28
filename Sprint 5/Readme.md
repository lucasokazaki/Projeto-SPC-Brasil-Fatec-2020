<h1>Sprint 5</h1>
<h2>Tarefas Desenvolvidas:</h2>

<li>Indicador de pontualidade no pagamento por cartão de crédito</li>
<li>Desenvolvimento da Interface Gráfica</li>
<li>Programação das funcionalidades do software</li>

<h3>Indicador de Pontualidade</h3>
Pontualidade de pagamento por pessoa: indica se a pessoa física está em dia ou não com o vencimento da fatura. 

Dados utilizados: na tabela de pagamento, contém dados de crédito, onde será verificado a data de vencimento da fatura com a data de pagamento do cliente. 

Cálculo: quanto maior o déficit de atraso menor a pontuação. 

<li>Antes da data de vencimento = peso 5</li>

<li>Pagamento na data de vencimento = peso 4 </li>

<li>Entre 1 a 7 dias de atraso = peso 3 </li>

<li>Entre 8 a 14 dias de atraso = peso 2 </li>

<li>Acima de 14 dias de atraso = peso 1</li> 

Por meio do indicador de pontualidade, classificamos os clientes conforme todos os pagamentos efetuados de forma individual. Assim, pontuando confome a data de pagamento, gerando uma média sobre o total de pagamentos realizados, para assim qualificar os clientes e gerar uma pontuação geral para os grupos de regiões do Brasil, com o intuito de indicar quais as regiões com melhor índice de pontualidade no pagamento por cartão de crédito e qual o perfil deste consumidor.

![IndicadorPontualidade](https://github.com/HenriqueNawa/Projeto-SPC-Brasil-Fatec-2020/blob/master/Gif/Indicador_pontualidade.png)

<h3>Interface Gráfica</h3>
