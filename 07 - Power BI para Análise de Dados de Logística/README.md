## Conteúdo do Capítulo 07

### Mini Projeto 4: Desconstruindo o Dashboard e Resolvendo Problemas de Análise na Área de Logística

Foi cedido um arquivo `.xlsx` contendo dados logísticos e um aqruivo `.pbix` com "erros" para serem resolvidos.
Foram resuisitadas as KPIs:
- Total de Entregas no Prazo Por Canal de Entrega;
- Percentual de Entregas Antecipadas Por Equipe de Entrega;
- Total de Entregas Por Mês;
- Total de Entregas de Produtos dos Top 5 Vendedores;
- Total de Entregas com Atraso Por Cidade; e
- Percentual de Entregas Por Status de Entrega.  

Uma visão do painel com problemas foi disponibilizada em `.pdf`.
### Execício proposto no primeiro vídeo do módulo:
Anotar e justificar os erros e problemas encontrados por mim no dashboard:  
- Total de Entregas no Prazo por Canal de Entrega (Area Chart Visual)  
    * Foi utilizado, no eixo y, a contagem de itens distintos em `Status_Entrega` ao em vez da contagem de `id_Pedido`. Mostrando, para cada item de `Canal_Entrega`, a quantidade de tipos diferentes de `Status_Entrega` encontrados.
    * Não foi filtrado o `Status_Entrega` como o título sugere (mas não houve diferença no gráfico final por conta do erro anterior).
    * Foi utilizado um visual difícil de distinguir baixas quantidades, prejudicando a informação passada.
- Total de Entregas Por Mês (Line Chart Visual)
    * Foi posta toda a hierarquia `Data_Entrega_Realizada` no eixo x, fazendo com que todos os dias fossem mostrados no visual e não somente os meses como o titulo sugere.
- Percentual de Entregas Por Equipe (Pie Chart Visual)

#### Anotações:

Não irei fazer alterações no arquivo `.pbix` disponibilizado, mas sim gerar um próprio a partir do meu modelo.

As KPIs solicitadas formam gráficos de baixa qualidade, pois o dataset possui chaves numéricas para as identificações, o que torna a leitura dificil de entender. 
