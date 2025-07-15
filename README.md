# 🌊 Inteligência Ambiental: Cenários de Risco por Poluição Plástica em Rios (2015–2060)

Este projeto utiliza dados de poluição fluvial por plásticos em escala global, com foco nos anos de 2015 e 2060, considerando diferentes cenários de ação climática. A análise explora padrões de risco ambiental, tendências de emissão e fatores socioeconômicos, com o objetivo de apoiar decisões estratégicas para políticas públicas, ONGs e financiadores internacionais.

---

## 🎯 Objetivo do Projeto

- Analisar a evolução da emissão de plásticos por país e por rio entre 2015 e 2060
- Avaliar correlações entre risco ambiental, PIB e população
- Identificar rios críticos mesmo sob cenários de mitigação
- Prever carga futura de plástico com base em dados socioeconômicos
- Agrupar países por perfil de risco e capacidade de ação
- Traduzir dados técnicos em recomendações estratégicas para decisões de impacto

---

## 📁 Dados Utilizados

- Fonte: [Kaggle – River Plastic Waste Risk Scenarios (2015 vs 2060)](https://www.kaggle.com/datasets/khushikyad001/river-plastic-waste-risk-scenarios-2015-vs-2060)
- Período: 2015 (base) e 2060 (projeções)
- Escopo: 100+ países e rios
- Cenários:  
  - `BAU` (Business As Usual): Sem mudanças estruturais  
  - `Mitigation`: Ações moderadas  
  - `Full Action`: Mudanças políticas robustas

---

## 🧠 Técnicas Utilizadas

| Tipo                   | Técnica Aplicada                                     |
|------------------------|------------------------------------------------------|
| Estatística Descritiva | Frequência, médias, desvio padrão                    |
| Visualização           | Boxplots, Pareto, heatmaps, barras, dispersão       |
| Regressão              | Linear, Random Forest Regressor                     |
| Correlação             | Spearman                                             |
| Clusterização          | K-Means                                              |
| Engenharia de Variáveis| Taxa de crescimento, emissão por PIB/população      |

---

## 💡 Perguntas Estratégicas Respondidas

1. Quais países e rios têm maior crescimento de emissão até 2060?
2. Risco ambiental se correlaciona com PIB ou população?
3. Quais rios permanecem críticos mesmo em cenário de mitigação?
4. É possível prever a emissão futura com variáveis socioeconômicas?
5. Quais perfis de risco ambiental emergem entre os países?
6. Quais recomendações práticas podem ser extraídas para políticas públicas?

---


---
# 📌 Executive Summary – Poluição Plástica Fluvial (MYK Ambiental)

Este resumo executivo apresenta os principais achados da análise de risco ambiental causada por emissões de plásticos em rios, com base em dados históricos de 2015 e projeções para 2060. O objetivo foi transformar dados técnicos em inteligência estratégica para priorização de ações e mitigação ambiental eficaz.

---

## 🔍 3 Principais Descobertas

### 1. 🌍 Países com Crescimento Acelerado de Emissão

Bangladesh (+157%) e Índia (+149%) lideram o crescimento percentual da carga plástica entre 2015 e 2060, mesmo sob cenários de mitigação. Isso evidencia um avanço crítico na poluição fluvial em países com rápido crescimento populacional e baixo índice de coleta de resíduos.

---

### 2. 🔁 Correlação Forte entre População e Carga Plástica

A análise de correlação de Spearman revelou um coeficiente de **r = 0.726** entre população e volume de plásticos direcionado aos rios. Isso demonstra que regiões densamente povoadas tendem a gerar maior risco, especialmente onde políticas públicas são frágeis.

---

### 3. 🛑 Rios de Alto Risco Não Respondem Bem à Mitigação

Mesmo sob cenário de políticas moderadas (Mitigation), rios como o **River_2547** e **River_1762** mantêm cargas superiores a 2.000 toneladas por ano. Esses rios apresentam resistência estrutural à mitigação passiva, exigindo medidas radicais.

---

## ✅ 3 Recomendações Estratégicas

### 1. 🎯 Intervenção Focada nos Rios Mais Críticos

Concentrar esforços em rios com alta emissão e baixa resposta à mitigação. Recomenda-se o uso de barreiras físicas, filtragem fluvial e campanhas comunitárias específicas, com monitoramento de KPIs ambientais.

---

### 2. 📊 Ações Direcionadas a Países com Baixo Índice de Coleta

Modelos de regressão indicaram que o **Waste Collection Rate** tem alto poder explicativo. Países como **Nigéria** e **República Democrática do Congo**, que pertencem ao Cluster de alto risco e baixa governança, devem ser prioritários para investimentos multilaterais.

---

### 3. 🌐 Formação de Alianças Regionais de Cooperação

Dada a transnacionalidade dos rios e o desequilíbrio de capacidade técnica, é recomendada a formação de consórcios de cooperação ambiental (governos + ONGs + empresas), com apoio internacional e metas claras até 2030.

---

Este estudo reforça a importância de análises estatísticas e visualizações executivas como instrumentos essenciais para transformar dados ambientais em decisões de alto impacto global.


## ✅ Conclusão e Próximos Passos

O projeto oferece evidências claras de como dados podem priorizar ações ambientais globais. Como evolução, este case pode ser estendido para:

- Adição de dados climáticos (chuvas, temperatura)
- Regressões espaciais com mapas interativos
- Conexão com dados de políticas ambientais reais por país

---

## 📜 Licença

Distribuído sob a [Licença MIT](./LICENSE). Uso livre com atribuição.

---

## ✒️ Autor

**Mayerikson Pereira**  
🔗 [LinkedIn](https://www.linkedin.com/in/mayerikson)  
💻 [GitHub](https://github.com/Mayerikson)


