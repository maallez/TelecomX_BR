



# Análise de Churn de Clientes - TelecomX

Foi feito uma análise exploratória dos dados de clientes da Telecom X identificando os fatores que contribuem para a evasão de clientes (Churn).
Tentando entender o comportamento dos clientes e fornecer insights para reduzir o Churn.

## Conteúdo do Notebook

O notebook contém as seguintes seções:

1.  **Carregamento de Dados:** Importação e inspeção inicial dos dados.
2.  **Limpeza e Tratamento de Dados:** Normalização de dados aninhados, tratamento de valores ausentes e conversão de tipos de dados.
3.  **Análise Exploratória de Dados:** Visualização e análise da distribuição de variáveis categóricas e numéricas em relação ao Churn.
4.  **Conclusões e Insights:** Resumo dos principais achados da análise.
5.  **Recomendações:** Sugestões baseadas nos insights para reduzir o Churn.

## Como Executar o Notebook

Para executar este notebook, você precisará ter o Google Colab ou um ambiente Python com as seguintes bibliotecas instaladas:

-   pandas
-   numpy
-   matplotlib
-   seaborn

Para melhorar a visualização do seu codigo pode ser necessario rodar `pd.set_option('future.no_silent_downcasting', True)` para remover o downcasting do metodo replace da biblioteca Numpy

Você pode abrir o notebook diretamente no Google Colab e executar as células sequencialmente. Certifique-se de que o arquivo de dados `TelecomX_Data.json` esteja acessível no ambiente de execução.

## Insights Principais

Com base na análise, alguns dos principais insights incluem:

-   Clientes com contratos mensais têm maior probabilidade de Churn.
-   O serviço de internet de fibra óptica está associado a uma maior taxa de Churn.
-   Clientes que utilizam cheque eletrônico como método de pagamento apresentam maior evasão.
-   Clientes com menor tempo de contrato (tenure) são mais propensos a cancelar.
-   Clientes com baixos gastos totais, especialmente no início do contrato, têm maior propensão ao Churn.

## Recomendações

As recomendações para reduzir o Churn incluem:

-   Incentivar contratos de maior duração com benefícios.
-   Investigar e resolver problemas com o serviço de fibra óptica.
-   Avaliar e melhorar o método de pagamento por cheque eletrônico.
-   Implementar programas de fidelidade para clientes iniciais.
-   Identificar e contatar proativamente clientes de baixo gasto.
-   Segmentar clientes com base no risco de Churn para ações direcionadas.

## Visualizações

O notebook possui varios graficos que podem ilustrar as distribuições de Churn por diferentes características do cliente.
