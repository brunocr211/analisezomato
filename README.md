Zomato-Analysis (criação de dashboards interativos usando Excel/Power BI/Tableau) e SQL
Objetivo do Projeto

O objetivo deste projeto é analisar os dados de restaurantes do Zomato para descobrir insights sobre tendências do setor, preferências dos clientes e principais fatores que influenciam avaliações e preços.
A meta é ajudar empresas, donos de restaurantes e stakeholders a tomarem decisões baseadas em dados para melhorar a qualidade do serviço, precificação do cardápio e satisfação dos clientes.

Base de Dados Utilizada

<a href="https://github.com/Rakshithabadiger/Zomato-Analysis/blob/main/Zomata%20-%20Copy.xlsx"> Dataset </a>

Processo

Compreensão dos Dados
Exploração do dataset para identificar variáveis principais, como nome do restaurante, localização, tipos de culinária, avaliações, votos, custo e opções de entrega online.
Verificação de valores ausentes, duplicados e outliers.

Limpeza e Preparação dos Dados
Remoção de registros duplicados e colunas irrelevantes.
Tratamento de valores ausentes com técnicas apropriadas de imputação.
Padronização dos nomes de colunas e formatação de dados categóricos (ex.: culinária, nomes de cidades).
Conversão de colunas numéricas para os tipos corretos de dados para análise.

Análise Exploratória de Dados (EDA)
Análise da distribuição de restaurantes por cidades e tipos de culinária.
Estudo das relações entre avaliações, votos e custos.
Comparação entre restaurantes que oferecem entrega online e os que não oferecem.
Visualização de tendências com gráficos de barras, mapas de calor e dashboards interativos.

Visualização e Dashboards
Construção de dashboards interativos no Power BI/Tableau para apresentar insights de forma clara.
Criação de KPIs principais como média de avaliações, distribuição de custos e culinárias mais populares.

Questões (KPIs e Gráficos)

Construir um Modelo de Dados usando as planilhas do arquivo Excel.

Criar uma Tabela Calendário usando a coluna Datekey_Opening (que contém as datas mínimas e máximas).
Adicionar as seguintes colunas na Tabela Calendário com fórmulas:

Ano

Número do Mês

Nome Completo do Mês

Trimestre (Q1, Q2, Q3, Q4)

AnoMês (YYYY-MMM)

Número do Dia da Semana

Nome do Dia da Semana

Mês Fiscal (Abril = FM1, Maio = FM2 … Março = FM12)

Trimestre Fiscal (com base no mês fiscal: FQ-1, FQ-2…)

Converter a coluna Average cost for 2 para dólares americanos (atualmente está em moedas locais).

Encontrar o número de restaurantes por cidade e país.

Identificar o número de restaurantes abertos por Ano, Trimestre e Mês.

Contar os restaurantes com base na média de avaliações.

Criar faixas de preço razoáveis baseadas no custo médio e calcular quantos restaurantes caem em cada faixa.

Calcular a porcentagem de restaurantes com “Has_Table_booking”.

Calcular a porcentagem de restaurantes com “Has_Online_delivery”.

Desenvolver gráficos baseados em culinária, cidade e avaliações (o candidato pode propor novos KPIs para análise).

Construir um Dashboard com os KPIs acima.

Também é possível experimentar com outros KPIs adicionais.

Dashboards

EXCEL <img width="1581" height="706" alt="Snapshot Dashboard Excel" src="https://github.com/user-attachments/assets/01ad263c-d2b8-4a70-8fa0-5a1eee2acc39" />

POWER BI <img width="1706" height="779" alt="Snapshot Dashboard Power BI" src="https://github.com/user-attachments/assets/bddbf4af-4b5f-449f-8501-34c022794dd3" />

TABLEAU <img width="1709" height="775" alt="Snapshot Dashboard Tableau" src="https://github.com/user-attachments/assets/11423a1c-be87-4569-b2fa-275d279287c4" />

Insights do Projeto

Cidades de Maior Desempenho: Grandes metrópoles como Bangalore, Delhi e Mumbai dominam o mercado de restaurantes.

Culinárias Populares: As culinárias indiana do norte e chinesa são as mais frequentes e preferidas.

Tendências de Avaliação: Restaurantes com entrega online e mais votos tendem a ter avaliações melhores.

Análise de Custos: Restaurantes bem avaliados geralmente mantêm faixas de custo moderadas, sugerindo que a relação custo-benefício influencia na satisfação do cliente.

Limpeza de Dados

Exclusão de colunas desnecessárias como url e address, que não agregavam valor analítico.

Remoção de registros inconsistentes em localização/culinária e padronização dos nomes de categorias.

Tratamento de valores ausentes em avaliações e custos para garantir visualizações corretas.

Conversão dos valores de custo para um formato de moeda uniforme para análise.

Consultas SQLs


## Final Conclusion
The analysis of Zomato’s restaurant data provides valuable insights into customer preferences, cost dynamics, and city-wise trends. Restaurants can leverage these findings to optimize their menus, pricing strategies, and service offerings. This project demonstrates how data cleaning, visualization, and exploratory analysis can transform raw data into actionable business intelligence.
