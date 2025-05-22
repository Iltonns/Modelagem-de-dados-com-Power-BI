# Projeto Neves Store - Modelagem Dimensional no Power BI

# 📊 Visão Geral
Implementação de um modelo estrela (star schema) no Power BI para análise de desempenho comercial da Neves Store, permitindo:
✅ Análise de vendas e estoque com dados históricos
✅ KPIs estratégicos para tomada de decisão
✅ Relacionamentos flexíveis para análises temporais e geográficas

# 🛠️ Ferramentas Utilizadas
<div style="display: flex; gap: 10px;"> <img src="https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=Power-BI&logoColor=black" alt="Power BI"/> <img src="https://img.shields.io/badge/DAX-FF9900?style=for-the-badge&logo=Power-BI&logoColor=white" alt="DAX"/> <img src="https://img.shields.io/badge/Power_Query-0066FF?style=for-the-badge&logo=Power-BI&logoColor=white" alt="Power Query"/> <img src="https://img.shields.io/badge/SQL_Server-CC2927?style=for-the-badge&logo=Microsoft-SQL-Server&logoColor=white" alt="SQL Server"/> <img src="https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=Microsoft-Excel&logoColor=white" alt="Excel"/> </div>
📂 Estrutura do Modelo Dimensional
# 🌟 Tabelas de Dimensões (7)
Cliente (Geografia, Segmentação)

Produto (Hierarquia: Categoria > Subcategoria)

Revendedor (Canal de Vendas)

Território (Região, País, Cidade)

Calendário (Chave artificial ddmmyyyy)

Modo de Envio

Status do Pedido

# 📊 Tabelas de Fatos (2)
Vendas (Pedidos, Receita, Margem)

Estoque (Nível de Estoque, Movimentação)

🔗 Relacionamentos (9)
Flexíveis (ativos/inativos para análise temporal)

Filtros cruzados entre dimensões e fatos

# ⚙️ Recursos Implementados
🔧 Transformações Avançadas (Power Query)
✔ Tratamento de datas (dd/mm/yyyy → ddmmyyyy como chave)
✔ Mesclagem de tabelas (Vendas + PedidoVendas)
✔ Normalização de nomes de colunas

# 📐 Modelagem Dimensional
✔ Tabela de calendário com chave artificial para análises temporais
✔ Hierarquias naturais (Produto > Categoria > Subcategoria)
✔ Relacionamentos ativos/inativos para análise histórica

# 📈 Medidas DAX (KPIs Críticos)
✔ Total de Pedidos (com contexto temporal ajustado)
✔ Total de Entregas (usando USERELATIONSHIP para dados de entrega)
✔ Disponibilidade de Estoque (estoque atual vs. demanda)

# 📌 Próximos Passos
🔹 Implementar previsão de demanda (Machine Learning)
🔹 Adicionar análise de satisfação do cliente
🔹 Dashboard interativo para equipe comercial

# 📥 Como Utilizar
Clone o repositório

Abra o arquivo .pbix no Power BI Desktop

Atualize a conexão com sua fonte de dados

<div align="center"> <img src="https://img.shields.io/badge/License-MIT-blue.svg" alt="License MIT"/> <img src="https://img.shields.io/badge/Status-Concluído-brightgreen" alt="Status"/> </div>
🎯 Objetivo Final
Transformar dados brutos em insights acionáveis para impulsionar as vendas e otimizar o estoque da Neves Store.

🚀 Vamos analisar os dados!
