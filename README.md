# Trabalho de Conhecimento de Base de Dados

Este repositório é um trabalho voltado ao conhecimento de base de dados, abrangendo os seguintes tópicos:

- Conhecimento do dataset
- Análise de distribuição
- Normalização/padronização
- Análise de variâncias entre atributos
- Análises de correlações

## Dataset

O dataset que foi utilizado para este trabalho é composto de indicadores de uma operação de Callcenter, objetificando em encontrar correlação entre os indicadores de performance e os resultados de venda ou nível de serviço. Ressalva-se que os testes não se limitam à bases do gênero falado anteriormente, mas para qualquer base com atributos contínuos 

## Análise de distribuição

Antes de realizar análises estatísticas nos dados, é importante verificar se eles seguem uma distribuição normal. Para isso, realizamos uma análise de distribuição utilizando testes estatísticos. Utilizamos distribuição gráfica com 3 tipos de gráficos para cada atributo, cálculo de curtose e assimetria, teste d'agostinho e teste de Shapiro Wilks, e os resultados são compilados na última função desse módulo.

## Normalização/padronização

Após a análise de distribuição, é importante normalizar ou padronizar os dados, de forma a evitar viés nas análises. Neste trabalho, utilizamos Z_Score, Normalização Máx_Min e transformação logarítmica

## Análise de variâncias entre atributos

Para entender a relação entre os atributos do dataset, realizamos análises de variância, que nos permitem verificar a variação de um atributo em relação aos outros. Utilizamos Teste de Levene e Bartlett. Os resultados são compilados na última função desse módulo.

## Análises de correlações

Além da análise de variâncias, também realizamos análises de correlações entre os atributos do dataset, para identificar possíveis relações entre eles. Utilizamos Teste de Spearman e Pearson. Há também o cálculo de KMO e MSA para verificarmos a explicação de cada atributo com relação ao conjunto que ele pertence. Os resultados são compilados na última função desse módulo.

## Como utilizar

Para utilizar este repositório, basta cloná-lo em sua máquina e executar os arquivos. Certifique-se de ter instalado as bibliotecas previamente. Observações à parte, estão descritas no decorrer do código.
