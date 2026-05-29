# 🏨 Análise e Tratamento de Dados Hoteleiros

Este projeto consiste na limpeza, tratamento e visualização de dados de uma base hoteleira utilizando **Python**, **Pandas** e **Plotly**. A atividade foi desenvolvida em ambiente Google Colab para automatizar processos de negócios e gerar insights visuais interativos.

## 📋 Requisitos do Negócio e Soluções

O projeto foi dividido em quatro etapas principais de tratamento de dados e análise visual:

1. **Limpar Idades Bizarras**: Filtra a base de dados para manter apenas hóspedes maiores de 18 anos e com no máximo 100 anos, atendendo às regras operacionais do hotel.
2. **Corrigir Faturamento (`Total_Charges`)**: Identifica e corrige falhas no sistema que geraram valores de faturamento negativos, convertendo-os em valores absolutos (positivos).
3. **Criar Nova Métrica (`Noites`)**: Calcula a quantidade de diárias de cada hóspede subtraindo a data de `Check-in` da data de `Check-out`.
4. **Visualização Interativa**: Geração de 3 gráficos analíticos dispostos lado a lado utilizando a biblioteca interativa **Plotly Subplots**.

---

## 🛠️ Tecnologias Utilizadas

*   [Python 3](https://python.org) - Linguagem de programação principal.
*   [Pandas](https://pydata.org) - Manipulação, filtragem e tratamento dos dados.
*   [Plotly](https://plotly.com) - Criação de gráficos dinâmicos e interativos.
*   [Google Colab](https://google.com) - Ambiente de desenvolvimento em nuvem.

---

## 📊 Gráficos Gerados

Os gráficos integrados lado a lado trazem as seguintes informações de forma dinâmica (permitindo zoom e detalhes ao passar o mouse):
*   **Gráfico 1:** Histograma com a distribuição detalhada da idade dos hóspedes (18 a 100 anos).
*   **Gráfico 2:** Histograma do faturamento (`Total_Charges`) corrigido, permitindo enxergar a concentração e a dispersão das receitas.
*   **Gráfico 3:** Gráfico de barras com escala de cores *Viridis* mapeando a quantidade de noites mais comuns por hospedagem.

---

## 🚀 Como Executar o Projeto

1. Abra o [Google Colab](https://google.com).
2. Faça o upload do arquivo contendo os dados do hotel (ex: `hotel_dados.csv`) na aba de arquivos lateral do Colab.
3. Copie o script python tratado no ambiente do caderno.
4. Execute as células para visualizar a tabela final limpa e a estrutura de gráficos interativos.

---

*Desenvolvido como atividade prática de análise de dados hoteleiros.*
