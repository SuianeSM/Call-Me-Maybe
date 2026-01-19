# Projeto Call Me Maybe — Identificação De Operadores Ineficientes
## Visão Geral

Projeto focado em diagnóstico operacional e tomada de decisão baseada em dados para a empresa de telefonia virtual CallMeMaybe. O objetivo é identificar operadores ineficientes a partir de métricas de chamadas recebidas, perdidas e realizadas, apoiando supervisores na gestão de desempenho.

## Objetivo de Negócio

Criar um modelo analítico que permita:

Identificar operadores com baixa eficiência operacional

Apoiar supervisores na priorização de ações corretivas

Subsidiar o desenvolvimento de uma nova funcionalidade do produto

Um operador é considerado ineficiente quando apresenta:

Alto volume de chamadas perdidas

Tempo excessivo de espera em chamadas recebidas

Baixo volume de chamadas ativas (para operadores outbound)

## Dados Utilizados
- telecom_dataset_us.csv

Registros diários de chamadas realizadas e recebidas:

Direção da chamada (in / out)

Chamadas internas e externas

Chamadas perdidas

Volume de chamadas

Duração da chamada e tempo total (incluindo espera)

- telecom_clients_us.csv

Informações cadastrais dos clientes:

Plano tarifário

Data de início do contrato

## Etapas do Projeto
**1. Decomposição de Tarefas**

Definição do problema de negócio

Diagnóstico inicial dos dados

Formulação de hipóteses mensuráveis

Definição de KPIs operacionais

Planejamento das análises e entregáveis

**2. Análise Exploratória de Dados (EDA)**

Avaliação de qualidade dos dados

Estatísticas descritivas

Análise de chamadas perdidas, duração e volume

Comparação entre operadores

**3. Testes Estatísticos**

Validação de hipóteses sobre desempenho

Comparação entre operadores eficientes vs ineficientes

Justificativa dos métodos estatísticos utilizados

**4. Identificação de Operadores Ineficientes**

Construção de métricas de eficiência

Classificação de operadores por performance

Segmentação por tipo de chamada (inbound / outbound)

## KPIs Principais

Taxa de chamadas perdidas

Tempo médio de espera

Volume de chamadas ativas

Duração média das chamadas

## Entregáveis

Jupyter Notebook com análise completa, código organizado e explicações em Markdown

Dashboard interativo com KPIs operacionais e filtros relevantes

Relatório final estruturado no formato CAR (Contexto, Ações, Resultados), com recomendações práticas para o negócio

## Resultado Esperado

O projeto entrega uma base analítica sólida para:

Monitorar desempenho de operadores

Apoiar decisões de gestão e treinamento

Evoluir o produto da CallMeMaybe com foco em eficiência operacional

Análise orientada a ação, com foco em impacto real no negócio.
