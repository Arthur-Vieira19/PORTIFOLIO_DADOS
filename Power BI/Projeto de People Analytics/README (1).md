# 👥 People Analytics — Dashboard de RH

Dashboard interativo em Power BI para monitoramento de 
indicadores estratégicos de Recursos Humanos, com foco 
em turnover, satisfação e distribuição de equipe.

---

## 🎯 Problema

Gestores de RH frequentemente tomam decisões sobre 
pessoas sem visibilidade consolidada dos dados da equipe.
Este projeto centraliza os principais indicadores em um 
único painel interativo, permitindo análise rápida e 
tomada de decisão orientada por dados.

---

## 📊 Indicadores Monitorados

| Indicador | Descrição |
|---|---|
| Total de Funcionários | Colaboradores ativos |
| Turnover (%) | Percentual de ex-funcionários |
| Salário Médio | Média salarial por cargo/área |
| Experiência Média | Tempo médio de casa |
| Distribuição por Gênero | Proporção F/M |
| Satisfação no Trabalho | Índice por departamento |
| Hora Extra | % da equipe com horas extras |
| Faixa Etária | Distribuição por treemap |

---

## 🔍 Principais Insights

- Departamentos com maior índice de hora extra 
  apresentam menor satisfação no trabalho
- Faixa etária predominante entre 30–40 anos, 
  com gap de retenção em colaboradores abaixo de 25
- Turnover concentrado em cargos operacionais



---

## 🛠️ Tecnologias e Técnicas

- **Power BI Desktop** — modelagem e visualização
- **DAX** — medidas calculadas:
  - `Turnover % = DIVIDE([Ex-Funcionários],[Total Funcionários])`
  - `Satisfação Média = AVERAGEX(Funcionários,[Satisfação])`
- **Modelagem relacional** — relacionamento entre 
  tabelas de funcionários, cargos e departamentos

---


## 📁 Dataset

- Fonte: Dataset público de RH *(IBM HR Analytics)*
- Linhas: X registros | Colunas: Y variáveis

---

## 👨‍💻 Autor

**Arthur Vieira** · [LinkedIn](https://linkedin.com/in/arthur-vieira-machado-dos-santos) · [GitHub](https://github.com/Arthur-Vieira19)

## 📷 Preview

> ![alt text](image.png)

---

## 👨‍💻 Autor

Desenvolvido por **Arthur Vieira**  
🔗 [GitHub](https://github.com/Arthur-Vieira19)
