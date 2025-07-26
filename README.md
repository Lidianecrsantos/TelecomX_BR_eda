# TelecomX_BR_eda
Projeto do curso da Alura

Análise de Evasão de Clientes (Churn) - TelecomX
Descrição do Projeto
Este projeto realiza uma análise exploratória abrangente do conjunto de dados de clientes da TelecomX com o objetivo de identificar os principais fatores que contribuem para a evasão de clientes (Churn). Através da limpeza, transformação e visualização dos dados, buscamos obter insights acionáveis para ajudar a TelecomX a reter seus clientes de forma mais eficaz.

Conjunto de Dados
O conjunto de dados utilizado para esta análise é o TelecomX_Data.json, disponível em: https://raw.githubusercontent.com/ingridcristh/challenge2-data-science/refs/heads/main/TelecomX_Data.json.

Ele contém informações sobre diversos clientes da TelecomX, incluindo dados demográficos, serviços contratados, informações de conta e status de evasão (Churn).

Análise Realizada
A análise foi conduzida em um notebook Google Colab e seguiu as seguintes etapas principais:

Extração de Dados: Carregamento dos dados a partir do arquivo JSON.
Transformação de Dados: Normalização das informações aninhadas, tratamento de valores ausentes/inconsistentes (especialmente na coluna Churn e Charges.Total), criação de novas features como Contas_Diarias e conversão de variáveis categóricas para formato numérico (One-Hot Encoding).
Análise Exploratória de Dados (EDA):
Análise descritiva das variáveis numéricas.
Visualização da distribuição da variável Churn (Gráfico 1).
Cálculo e visualização da matriz de correlação entre as variáveis numéricas e Churn (Gráfico 2).
Análise da distribuição de Churn por variáveis categóricas importantes (Gráfico 3).
Análise da distribuição de variáveis numéricas por Churn (Gráfico 4).
Principais Conclusões e Insights
A análise exploratória revelou diversos fatores importantes associados à evasão de clientes:

Clientes com contratos mensais e que utilizam serviço de internet de fibra óptica apresentam maior tendência a evadir.
A falta de assinatura de serviços adicionais como segurança online, suporte técnico, backup e proteção de dispositivo está fortemente correlacionada com a evasão.
Clientes com menor tempo de contrato (tenure) têm maior probabilidade de cancelar o serviço.
Embora clientes que evadem tenham cobranças mensais mais altas, o total gasto ao longo do tempo é menor devido ao menor período de contrato.
O método de pagamento cheque eletrônico também mostrou associação com a evasão.
Estes insights sugerem que a evasão pode ser influenciada por uma combinação de fatores relacionados ao tipo de contrato, serviços adicionais contratados, tempo de relacionamento com a empresa e método de pagamento.

Recomendações
Com base nos insights obtidos, sugerimos as seguintes ações para reduzir a evasão:

Criar programas de retenção específicos para clientes com contratos mensais.
Investigar a satisfação dos clientes de fibra óptica e resolver possíveis problemas.
Promover os benefícios dos serviços adicionais para aumentar a adesão.
Analisar e possivelmente otimizar o processo de pagamento via cheque eletrônico.
Implementar um sistema de alerta precoce para identificar clientes em risco com base nos fatores identificados.
Como Executar o Notebook
Para replicar esta análise, você pode abrir o notebook Google Colab e executar as células sequencialmente. 

