### Python Insights: Analisando Dados com Python
#### Webnar Hashtag - Taxa de Churn

Neste projeto foi realizado o cálculo de probabilidade de Churn de uma empresa provedora de internet que trabalha com planos mensais, trimestrais e anuais. 
Análise feita com bibliotecas Pandas e Plotly
Segue o passo a passo para a análise:

- Passo 1: Importar base de dados
- Passo 2: Visualizar a base de dados
- Passo 3: Tratamento de dados
- Passo 4: Analise dos cancelamentos
- Passo 5: Analise das causas dos cancelamentos

### Insights a partir da linha 11:

1º Ponto - Aqui já temos o insight de que TODOS os contratos MENSAIS foram cancelados

2° Ponto - Todos que atrasaram o pagamento 20 dias, cancelaram

3º Ponto - Todos que ligaram ao Call Center + de 5 vezes, cancelara

Possíveis resoluções:

1º Ponto - Deixarmos os planos anuais e trimestrais mais atrativos
2º Ponto - Criar um aviso para quando o pagamento estiver 10 dias atrasado
3º Ponto - Resolver o problema pelo Call Center, com apenas 1 ligação
