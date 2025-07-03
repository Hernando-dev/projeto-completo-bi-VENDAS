# projeto-completo-bi-VENDAS
Dashboard completo de Análise e Previsão de Vendas utilizando dados da NEOTASS (2020–2022). Projeto desenvolvido com Python, Pandas, Plotly, ARIMA e widgets interativos no Google Colab, focado em insights visuais, análise de desempenho, devoluções e projeção de faturamento.
# 📊 Projeto de Análise e Previsão de Vendas | NEOTASS

Este projeto foi desenvolvido com o objetivo de consolidar e analisar dados de vendas, produtos, clientes, lojas e devoluções da empresa NEOTASS, utilizando Python e bibliotecas voltadas para análise de dados, visualização interativa e modelagem preditiva.

Foram utilizadas ferramentas como **Google Colab**, **Plotly**, **Pandas** e o modelo **ARIMA**, permitindo a geração de dashboards interativos, KPIs estratégicos e uma projeção de vendas para os próximos 12 meses.

---

## 📌 Objetivos do Projeto

- 🧼 Tratar, limpar e unificar múltiplas bases de dados (.xlsx).
- 📊 Criar gráficos e indicadores interativos de fácil interpretação.
- 🔍 Gerar insights estratégicos por meio de análises temporais, geográficas e por categoria.
- 📈 Projeção de vendas futuras com técnicas de séries temporais (ARIMA).
- 💡 Suporte à tomada de decisão por meio de visualizações e comparações históricas.

---

## 🗂️ Estrutura do Projeto

```bash
├── notebooks/
│   └── projeto_analise_vendas_neotass.ipynb
├── data/
│   └── (pastas com os arquivos Excel)
├── README.md
├── requirements.txt
└── vendas_completo.csv (output final)
📥 Bases Utilizadas
Arquivo	Descrição
Base Vendas - 2020/2021/2022	Vendas realizadas por SKU, cliente, loja e data
Cadastro Produtos.xlsx	Tabela mestre de produtos com preço, categoria e custo
Cadastro Clientes.xlsx	Perfil dos clientes (sexo, escolaridade, ID, etc.)
Cadastro Lojas.xlsx	Informações das lojas e seus colaboradores
Cadastro Localidades.xlsx	Localização geográfica das lojas (cidade, estado, etc.)
Base Devoluções.xlsx	Registros de devoluções e motivos por SKU e loja

📈 Principais Análises Realizadas
✅ Dashboard Interativo com Filtros de Ano e Intervalo de Anos:

Comparativo de vendas mensais (YTD)

Ranking de lojas por faturamento

Faturamento por categoria e por colaborador

Ticket médio geral

Faturamento por estado/continente

Devoluções por motivo, estado e produto

Mapa de calor de correlação entre variáveis numéricas

✅ Previsão de Vendas:

Modelo ARIMA (1,1,1) para prever os próximos 12 meses com gráfico de tendência

Exibição de tabela com datas futuras e faturamento estimado

🧠 Tecnologias e Bibliotecas Utilizadas
Python 3.10+

Google Colab

pandas, openpyxl, matplotlib, seaborn, plotly, ipywidgets

statsmodels (modelo ARIMA)

🚀 Como Executar
Monte seu Google Drive no Google Colab:

python
Copiar
Editar
from google.colab import drive
drive.mount('/content/drive')
Crie uma pasta chamada NEOTASS_BASES com os arquivos Excel dentro.

Instale as dependências:

bash
Copiar
Editar
!pip install -q pandas==2.2.2 openpyxl plotly matplotlib seaborn statsmodels
Execute o notebook projeto_analise_vendas_neotass.ipynb passo a passo.

📌 Principais KPIs Criados
📌 Faturamento Total

📌 Ticket Médio Geral

📌 Top 10 Produtos mais vendidos

📌 Top 10 Produtos com maior taxa de devolução

📌 Projeção de Faturamento para os próximos 12 meses

📌 Análise de impacto de colaboradores no faturamento

📌 Taxa de devolução por estado (região)

📤 Exportação
Ao final da execução, um arquivo vendas_completo.csv será salvo com todos os dados tratados e prontos para uso externo ou importação em sistemas de BI (Power BI, Tableau, etc).

📌 Melhorias Futuras
Integração com Streamlit para publicação do dashboard em nuvem.

Uso de Dash ou Power BI Embedded para visualização empresarial.

Implementação de modelo SARIMA ou Prophet para comparar a performance do ARIMA.

Aplicar validações automatizadas nas cargas dos arquivos.

👨‍💻 Autor
Ernando Costa
Análise de Dados | BI | Python | Power BI | Machine Learning
📧 Email:ernandoferreiradacosta@gmail.com
🔗 LinkedIn

