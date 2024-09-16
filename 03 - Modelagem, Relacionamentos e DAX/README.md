## Conteúdo do Capítulo 03

### Laboratório Prático 2: Dashboard de Vendas, Custo, Margem de Lucro e KPI

Foi cedido um arquivo `.zip` contendo quatro arquivos `.csv` com dados de venda e dimensões de vendas (pedido, produto e cliente), inicialmente não foram propostas questões a serem respondidas com os dados, portanto, irei somente tratar os dados, se necessário, e configurar seus relacionamentos.  

> As unicas alterações necessárias para relacionar os dados apropriadamente eram as remoções de instâncias duplicadas em [Pedido] e [Produto]. 
> Mantive os visuais como estão na matriz, somente alterei o título e versão da primeira página.  

Agora, iniciarei as aulas.

Ao longo das aulas foram passadas as questões:  
1. Qual foi o total de valor venda considerando cada modo de envio dos pedidos? Use um gráfico de cascata. 
    ``` 
    Verificou-se os valores:
      Classe Padrão,    $ 7.556.488,21;
      Segunda Classe,   $ 2.565.561,05;
      Primeira Classe,  $ 1.843.147,32;
      Mesmo Dia,        $   677.305,33; e
      o Total Geral de: $12.642.501,91.
    ```
2. Quais mercados tiveram o maior custo médio de envio dos produtos vendidos? Use um gráfico treemap.  
    ```
    Os quatro mercados com maior média de custo de envio são:
      APAC,  $29,14;
      US,    $28,94;
      EU,    $27,28;
      LATAM, $26,46.
    Que compõem mais de 50% do da soma dos valores médios. 
    ```
3. A empresa tem como objetivo (meta) manter uma média de 350 para o valor de venda todos os meses. Mostre um indicador (KPI– Key Performance Indicator) com o valor médio de venda. A empresa ficou abaixo ou acima da meta no mês de Abril/2014?  
    ```
    Utilizando a seleção do o mês e ano em questão no visual da questão 5, percebe-se que a meta não foi alcançada ficando $120,38 abaixo da mesma.
    ```
4. Considere que o lucro é equivalente a: [valor venda] - [custo envio]. Qual categoria de produto apresentou maior lucro médio?  
    ```
    Tecnologia teve o maior lucro médio, com $417,86.
    ```
5. Qual foi o comportamento da margem de lucro ao longo do tempo? Considere a margem de lucro como o lucro dividido pelo valor venda.  
    ```
    Percebe-se que a margem de lucro média ao longo dos meses está entre 88% e 90%.
    ```

#### Anotações:
Por falha minha, as respostas foram respondidas erradas nas questões 1 e 2. Não percebi a seleção de "Tecnologia" no gráfico da questão 4 e coletei as informações para esta categoria. Nesta versão, estão corrigidos.
A implementação do "Gauge Meter", por ser mais sensata para a questão 3, foi feita na versão final.
Foi reorganizada a ordem dos visuais para acomodar a implementação do visual citado acima e para desobstruir as legendas de outros visuais.