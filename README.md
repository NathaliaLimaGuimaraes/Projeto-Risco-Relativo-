# Projeto-Risco-Relativo
No contexto recente, a diminuição das taxas de juros no mercado desencadeou um aumento significativo na demanda por solicitações de crédito. Os clientes veem uma oportunidade favorável para financiar compras importantes ou consolidar dívidas existentes, o que levou a uma afluência de solicitações de empréstimo no banco "Super Caja". A equipe de análise de crédito do banco está enfrentando uma carga de trabalho avassaladora devido à análise manual necessária para cada solicitação de empréstimo de clientes individuais. Essa metodologia manual resultou em um processo ineficiente e demorado, afetando negativamente a eficácia e a rapidez com que as solicitações de empréstimo são processadas. A situação se torna mais crítica devido à crescente preocupação com a taxa de inadimplência, um problema que está afetando cada vez mais a indústria financeira, aumentando a pressão sobre os bancos para identificar e mitigar os riscos associados ao crédito.


## Objetivo
O objetivo da análise é identificar o perfil de clientes com risco de inadimplência, montar uma pontuação de crédito através da análise de dados e avaliar o risco relativo, possibilitando assim, classificar os clientes e futuros clientes em diferentes categorias de risco com base na sua probabilidade de inadimplência. Esta classificação permitirá ao banco tomar decisões informadas sobre a quem conceder crédito, reduzindo assim o risco de empréstimos não reembolsáveis. Além disso, a integração destas métricas fortalecerá a capacidade do modelo de identificar riscos, contribuindo para a solidez financeira e a eficiência operacional do Banco.

## Hipóteses
1)**Os mais jovens correm um risco maior de não pagamento - CONFIRMADA**

2)**Pessoas com mais empréstimos ativos correm maior risco de serem maus pagadores - REFUTADA**

3)**Pessoas que atrasaram seus pagamentos por mais de 90 dias correm maior risco de serem maus pagadores - CONFIRMADA**

## Equipe
Nathalia Guimarães

## Ferramentas e Tecnologias Utilizadas
- Google BigQuery
- Google Colab
- Apresentação Canva
- Google Looker Studio

## Linguaguens
1. linguagem SQL no BigQuery 
2. Python no Google Colab

## Links Ferramentas Aplicadas no Projeto  
Python - https://colab.research.google.com/drive/1xl75yeQ8V_pfyl2QZK9GyaVO5QcmHU1-?hl=pt-BR#scrollTo=IjU-WDHXVYWA

Looker Studio - https://lookerstudio.google.com/u/0/reporting/4838a2b1-c703-465c-aea4-2877d3960815/page/p_z2tpvisbjd/edit

Bigquery https://console.cloud.google.com/bigquery?hl=pt-br&project=projeto-risco-relativo-424616&supportedpurview=project&ws=!1m5!1m4!4m3!1sprojeto-risco-relativo-424616!2sdataset!3sRisco_Relativo_Categoria_AtrasodePagto!1m5!1m4!1m3!1sprojeto-risco-relativo-424616!2sbquxjob_1e62541d_190cc0c9302!3ssouthamerica-east1

## Base de Dados
Link para Data.set > https://drive.google.com/file/d/1jCm5ValysL41zP85jd1KmsDM5wW9y4S9/view

## Ficha técnica
Link para Ficha Técnica > https://www.notion.so/Projeto-Risco-Relativo-3664b9c0b5b84bdaabf79e95eb64a76c

## Resultados e Conclusões 
Para mais detalhes, consultar o relatório completo no looker Studio:[Relatório Looker Studio](https://lookerstudio.google.com/u/0/reporting/4838a2b1-c703-465c-aea4-2877d3960815/page/6Jb5D)
![dashboard risco relativo](https://github.com/user-attachments/assets/3a2e94b5-eeee-4c56-8b35-72aab603c9c6)



## ⚠️ Limitações e Próximos Passos 
Criar uma pontuação (score) para os clientes através da análise das variáveis categóricas. A pontuação pode ser a soma das categorias criadas para as variáveis ​​analisadas, para isso você pode transformar essas variáveis ​​em variáveis dummy que posteriormente podem ser somadas e assim criar a pontuação que utilizaremos nesta análise.Variáveis ​​dummy, também conhecidas como variáveis ​​indicadoras ou variáveis ​​binárias, são usadas em estatísticas e análises de regressão para representar informação qualitativa ou categórica em modelos que requerem variáveis ​​numéricas. Essas variáveis ​​assumem valores de 0 ou 1 para indicar a presença ou ausência de uma característica especial.

No contexto de regressão, variáveis ​​dummy são usadas para lidar com variáveis ​​​​categóricas, permitindo que o modelo capture o efeito dessas categorias na variável de resposta. Também é usado em análise de séries temporais, desenho experimental e outros contextos onde é necessário representar informações categóricas de maneira numérica.
