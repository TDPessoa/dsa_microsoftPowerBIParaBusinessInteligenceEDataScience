## Conteúdo do Capítulo 08

### Mini Projeto 5: Dashboard de Análise Financeira  

Foi cedido um arquivo `.xlsx` contendo dados financeiros.
Foram requisitadas as análises:
1. Total de Receitas
1. Total de Despesas
1. Margem de Lucro
1. Total de Receitas Por Componente
1. Total de Despesas Por Componente em relação à média de Despesas
1. Total de Receitas e Despesas Por Componente e Por  Ano, com a hierarquia Tipo/Componente.
- Além disso a empresa precisa identificar os segmentos onde Receitas e Despesas são maiores e menores a fim de traçar seu plano estratégico.  
  
Também foi sugerido um resultado final, exemplificado por uma imagem, anexada como `ObjetivoProposto.pdf` neste projeto. Irei realizar a primeira parte sem consultar dito exemplo.
  
#### Anotações:
O dataset contém 12 linhas e 38 colunas, sendo as duas primeiras colunas de dados categóricos e as outras 36 têm como titulos as datas iniciais dos meses dos anos de 2019, 2020 e 2022;  
Visto que se trata de uma consulta de dados cruzados, achei conveniente desfazer o cruzamento para que as colunas mês a mês virassem valores, transformando o dataset para 432 linhas e 4 colunas.

#### Anotações após ver as aulas:  
Não entendi que a média de despesas na questão 5 era da geral, então fiz o que era mais agradável aos olhos, uma despesa média de cada componente.  
A questão da 6 também foi mal interpretada, mas não tenho tanto apreço por visuais de tabela/matriz, 
Também não me atentei que a ultima questão era pra ser um visual diferente das demais. A mesma foi incluída na resposta final, mas com ressalvas:
    - Por conta do valor ser sempre positivo, não acho certo ser tratado da mesma forma para ambos os tipos, então fiz uma nova coluna e uma medida de soma que calculam o valor real, positivo ou negativo.
