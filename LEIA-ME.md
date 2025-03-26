# Projeto Neves Store - Modelagem de Dados no Power BI
Modelo dimensional completo para análise de vendas e estoque

# Visão Geral
Implementação de um modelo estrela (star schema) no Power BI para análise de desempenho comercial da Neves Store, contendo:

7 tabelas de dimensões (Cliente, Produto, Revendedor, Território, Calendário, etc.)

2 tabelas de fatos (Vendas e Estoque)

9 relacionamentos otimizados

Medidas DAX para KPIs críticos (Total de Pedidos, Total de Entregas)

# Recursos Implementados
✔ Transformações avançadas no Power Query:

Tratamento de datas (formato dd/mm/yyyy → ddmmyyyy como chave)

Mesclagem de tabelas (Vendas + PedidoVendas)

Normalização de nomes de colunas

✔ Modelagem dimensional:

Tabela de calendário com chave artificial

Hierarquias naturais (Produto > Categoria > Subcategoria)

Relacionamentos ativos/inativos para análise temporal

✔ Medidas DAX:

Total entregas com USERELATIONSHIP para datas de entrega

Total pedidos com contexto temporal ajustado
