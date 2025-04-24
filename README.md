# Relatório Final – Análise das Lojas do Senhor João

Este projeto contém a análise do desempenho de quatro lojas pertencentes ao Senhor João. A análise foi feita com base em dados de vendas, avaliações de clientes e custos de frete. O objetivo é identificar qual loja apresenta o pior desempenho geral e, portanto, deve ser fechada.

## Dados Utilizados

Os dados utilizados para esta análise foram retirados de arquivos CSV hospedados no GitHub. Cada arquivo contém informações sobre as vendas, categorias de produtos, avaliações de clientes e custos de frete para cada uma das lojas.

- **Loja 1**: [loja_1.csv](https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science/refs/heads/main/base-de-dados-challenge-1/loja_1.csv)
- **Loja 2**: [loja_2.csv](https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science/refs/heads/main/base-de-dados-challenge-1/loja_2.csv)
- **Loja 3**: [loja_3.csv](https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science/refs/heads/main/base-de-dados-challenge-1/loja_3.csv)
- **Loja 4**: [loja_4.csv](https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science/refs/heads/main/base-de-dados-challenge-1/loja_4.csv)

**Bibliotecas utilizadas**: 
- `pandas` (para manipulação e análise de dados);
- `matplotlib` e `seaborn` (para visualizações gráficas);
- 
## Como Rodar o Projeto

Para rodar a análise, basta abrir o notebook [Projeto_Analise_de_lojas_alura.ipynb] no Google Colab.

- **Google Colab**: Você pode abrir este notebook diretamente no Google Colab e executar as células de forma interativa.

## Análise dos Dados

### 1. Faturamento Total
O faturamento representa quanto cada loja arrecadou com as vendas. Os valores foram:

- **Loja 1**: R$ 1.534.509,12
- **Loja 2**: R$ 1.488.459,06
- **Loja 3**: R$ 1.464.025,03
- **Loja 4**: R$ 1.384.497,58

A **Loja 4** teve o menor faturamento entre as lojas.

### 2. Categorias Mais e Menos Vendidas
Em todas as lojas, as categorias **móveis** e **eletrônicos** estão entre as mais vendidas. No entanto, a **Loja 4** teve um desempenho mais fraco em algumas dessas categorias, como móveis e eletrônicos, que são importantes para o faturamento.

### 3. Avaliação Média das Lojas
A média das avaliações dos clientes foi a seguinte:

- **Loja 1**: 3,98
- **Loja 2**: 4,04
- **Loja 3**: 4,05
- **Loja 4**: 4,00

A **Loja 1**, apesar de ter um faturamento maior, obteve a pior avaliação entre as lojas.

### 4. Produtos Mais e Menos Vendidos
#### Mais Vendidos:
- **Loja 1**: Guarda roupas
- **Loja 2**: Iniciando em programação
- **Loja 3**: Kit banquetas
- **Loja 4**: Cama box

#### Menos Vendidos:
- **Loja 1**: Celular ABXY
- **Loja 2**: Jogo de tabuleiro
- **Loja 3**: Blocos de montar
- **Loja 4**: Guitarra

Observa-se que a **Loja 4** tem o pior desempenho no que diz respeito aos produtos vendidos, tanto no ranking de mais vendidos quanto de menos vendidos.

### 5. Frete Médio
O custo médio do frete para cada loja foi:

- **Loja 1**: R$ 34,69
- **Loja 2**: R$ 33,62
- **Loja 3**: R$ 33,07
- **Loja 4**: R$ 31,28

Embora a **Loja 4** tenha o menor valor de frete, o seu desempenho geral em vendas e avaliações é inferior.

## Conclusão

Com base nas análises, concluímos que a **Loja 4** apresenta o pior desempenho geral, apesar de ter o frete mais barato. Com o menor faturamento, o pior desempenho em vendas de produtos e uma avaliação média dos clientes não competitiva, a Loja 4 deve ser fechada.

A **Loja 1**, apesar de ter um faturamento maior, tem um desempenho semelhante em termos de produtos vendidos e avaliações, o que a coloca em uma posição intermediária.

Portanto, a recomendação é que o Senhor João **feche a Loja 4**, devido ao seu desempenho financeiro e de vendas insatisfatório, mesmo com o custo de frete mais baixo.

---
