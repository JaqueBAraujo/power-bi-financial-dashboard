# Desafio 05 — Dashboard de Análise Financeira com Power BI

## Sobre o projeto

Este projeto apresenta o desenvolvimento de um dashboard de análise financeira utilizando o **Power BI Online**, com base no conjunto de dados de exemplo *Financial Sample*.

O objetivo é aplicar conhecimentos de modelagem de dados, relacionamentos, linguagem DAX e visualização de indicadores financeiros.

O desenvolvimento foi realizado em ambiente macOS, utilizando a versão web do Power BI.

## Modelagem de dados

O modelo semântico foi organizado com as seguintes tabelas:

- **Financials:** dados financeiros de vendas.
- **D_Produtos:** dimensão de produtos.
- **D_Produtos_Detalhes:** informações complementares dos produtos.
- **D_Descontos:** informações sobre descontos.
- **D_Calendario:** dimensão de datas.

Foram configurados relacionamentos de cardinalidade um para muitos (1:N), permitindo a análise dos dados por produto e período.

## Indicadores financeiros

O dashboard apresenta três indicadores principais:

| Indicador | Resultado |
|---|---|
| Total de Vendas | 118,73 milhões |
| Total de Lucro | 16,89 milhões |
| Margem de Lucro | 14,23% |

Os resultados correspondem ao conjunto de dados utilizado, sem filtros de período aplicados.

## Análises visuais

Foram desenvolvidas as seguintes visualizações:

- Cartões de indicadores financeiros.
- Gráfico de linhas com a evolução mensal das vendas.
- Gráfico de barras horizontais com vendas por produto.
- Segmentação de dados por ano (2013 e 2014).

## Recursos utilizados

- Power BI Online
- Power BI Semantic Model
- DAX
- Modelagem dimensional
- Relacionamentos entre tabelas
- Visualizações interativas

## Resultados e aprendizados

O projeto permitiu praticar a criação de um modelo semântico, a configuração de relacionamentos, a construção de medidas financeiras e a organização de um dashboard interativo.

Também foi possível validar o funcionamento dos filtros e observar como as seleções realizadas nos gráficos afetam os indicadores apresentados.

## Ambiente de desenvolvimento

**Sistema operacional:** macOS  
**Ferramenta:** Power BI Online  
**Base de dados:** Financial Sample

## Evidência do projeto

A captura de tela do dashboard final será adicionada a este repositório para demonstrar os resultados obtidos.
