# 📊 Dashboard e Análise de Vendas com Streamlit: 
Este projeto tem como objetivo criar **duas aplicações interativas** utilizando **Streamlit**, para explorar e visualizar dados de vendas obtidos via API.
---

## 🚀 Tecnologias Utilizadas
- **Python 3.10+**
- **Streamlit**
- **Pandas**
- **Requests**
- **Plotly**
---

## 📂 Estrutura do Projeto
- `Dados Brutos.py` → Aplicação para **explorar os dados brutos**, aplicar **filtros interativos** e **baixar CSVs personalizados**.
- `Dashboard.py` → Dashboard de vendas com **métricas, gráficos interativos e filtros dinâmicos**.
---

## 🔎 Funcionalidades

### 📑 Dados Brutos
- Seleção de colunas.
- Filtros por:
  - Produto, Categoria, Preço, Frete, Data de compra.
  - Vendedor, Local da compra, Avaliação, Tipo de pagamento.
  - Parcelamento.
- Download dos dados filtrados em CSV.

### 📊 Dashboard de Vendas
- Filtros por Região, Ano e Vendedores.
- **Métricas em tempo real**: Receita total e quantidade de vendas.
- **Gráficos interativos** com Plotly:
  - Receita e Vendas por Estado (mapa geográfico).
  - Evolução mensal.
  - Top categorias e vendedores.
- Navegação por abas: Receita, Quantidade de Vendas e Vendedores.
