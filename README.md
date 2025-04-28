# Alura Store - Análise de Vendas

Este repositório contém o notebook `AluraStoreBr.ipynb` com a análise de vendas de diferentes lojas, realizada como parte do desafio 1 do curso de Data Science da Alura.

## Sumário

- [Visão Geral](#visão-geral)
- [Instalação](#instalação)
- [Uso](#uso)
- [Dados](#dados)
- [Resultados](#resultados)
- [Estrutura do Repositório](#estrutura-do-repositório)
- [Contato](#contato)

## Visão Geral

Neste projeto, unimos dados de quatro lojas diferentes para realizar análises como:

- Soma total dos preços dos produtos
- Quantidade de vendas por categoria em cada loja
- Média de avaliação das compras por loja
- Identificação dos produtos mais e menos vendidos
- Cálculo do frete médio por loja
- Visualizações gráficas para auxiliar na interpretação

## Instalação

1. Clone este repositório:
   ```bash
   git clone https://github.com/SEU_USUARIO/NOME_DO_REPOSITORIO.git
   ```
2. Acesse a pasta do projeto:
   ```bash
   cd NOME_DO_REPOSITORIO
   ```
3. Instale as dependências (se necessário):
   ```bash
   pip install pandas matplotlib
   ```
4. Abra o notebook no Jupyter ou no Google Colab.

## Uso

1. Verifique os links das bases de dados no início do notebook.
2. Execute as células em ordem para carregar os dados, processar e gerar as visualizações.
3. Ajuste parâmetros conforme necessário (ex.: caminhos de arquivos locais ou filtros).

## Dados

As bases são CSVs hospedadas em repositórios públicos da Alura:

- `loja_1.csv`
- `loja_2.csv`
- `loja_3.csv`
- `loja_4.csv`

Cada arquivo contém colunas como `Produto`, `Categoria`, `Preço`, `Frete` e `Avaliação da compra`.

## Resultados

- **Soma dos preços:** R$ 1.534.509,12
- **Categorias mais vendidas:** Eletrônicos, Moda, etc.
- **Média de avaliação:** Loja 3 com 4.75
- **Produto mais vendido:** Camiseta Básica
- **Frete médio:** varia entre R$ 18,75 e R$ 25,30

Inclui gráficos de barras e pizza para facilitar a visualização das métricas.

## Estrutura do Repositório

```plaintext
├── AluraStoreBr.ipynb    # Notebook com a análise
├── README.md            # Documentação deste repositório
└── data/                # (Opcional) Dados locais, se usados
    ├── loja_1.csv
    ├── loja_2.csv
    ├── loja_3.csv
    └── loja_4.csv
```
