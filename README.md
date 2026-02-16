# rocket-dev-estatisticas

Análise de estatísticas de faturamento em Python usando **pandas** e **matplotlib**.

## O que o projeto faz

O notebook `statistics.ipynb`:

- **Carrega os dados** de faturamento (data de referência e valor em R$) em um DataFrame
- **Calcula a média das vendas** (ex.: R$ 642.083,33)
- **Converte datas** para o tipo `datetime` e formata para exibição (dd/mm/aaaa)
- **Gera visualizações**:
  - Gráfico de **barras**: faturamento por data
  - Gráfico de **linha**: evolução do faturamento ao longo do tempo

## Requisitos

- Python 3.11
- pandas
- matplotlib

## Como rodar

1. Clone o repositório e entre na pasta do projeto.

2. Crie o ambiente e instale as dependências com Pipenv:

   ```bash
   pipenv install
   ```

3. Ative o ambiente e abra o Jupyter:

   ```bash
   pipenv shell
   ```

4. Execute as células do notebook na ordem para reproduzir a análise e os gráficos.
