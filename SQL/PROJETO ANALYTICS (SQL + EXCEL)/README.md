# 📊 Dashboard de Acompanhamento de Vendas

Pipeline completo de análise de vendas: desde a extração
de dados via SQL até a visualização executiva em Excel.

---

## 🎯 Problema

Operações comerciais precisam monitorar performance de
vendas, canais e comportamento de clientes em tempo real.
Este projeto responde 5 perguntas de negócio críticas
usando SQL sobre um banco relacional de vendas.

---

## 🔄 Arquitetura do Projeto

SQL (PostgreSQL) → Resultados exportados → Dashboard Excel

---

## 📌 Perguntas de Negócio Respondidas

| # | Pergunta | Técnica SQL |
|---|---|---|
| 1 | Receita, leads e conversão mês a mês | CTE + JOIN + date_trunc |
| 2 | Top 5 estados com mais vendas | GROUP BY + ORDER BY |
| 3 | Marcas mais vendidas no mês | JOIN + filtro por período |
| 4 | Lojas com maior volume | JOIN + ranking |
| 5 | Dias da semana com mais visitas | EXTRACT + CASE WHEN |

---

## 🔍 Principais Insights

- Pico de visitas ao site nas **segundas-feiras** (1.301 visitas)
- **SP** lidera em volume de vendas (734), seguido de MG (142)
- **FIAT** e **CHEVROLET** são as marcas mais vendidas
- Ticket médio mensal em torno de **R$ 48–52k**
- Taxa de conversão de leads varia entre **3,7% e 19,2%**

---

## 🛠️ Técnicas Aplicadas

**SQL (PostgreSQL)**
- CTEs (WITH)
- JOINs entre múltiplas tabelas
- date_trunc para agrupamento mensal
- EXTRACT + CASE WHEN para análise por dia da semana
- Filtros por período e ranking com LIMIT

**Excel**
- Dashboard executivo com KPIs consolidados
- Aba de resultados estruturada por análise
- Visualizações integradas aos dados SQL

---

## 📁 Estrutura

PROJETO ANALYTICS(SQL + EXCEL)/
├── DashBoard_acompanhamento_de_vendas.sql
├── Dashboard_de_vendas.xlsx
└── README.md

---

## 👨‍💻 Autor
**Arthur Vieira** ·
[LinkedIn](https://linkedin.com/in/arthur-vieira-machado-dos-santos) ·
[GitHub](https://github.com/Arthur-Vieira19)
