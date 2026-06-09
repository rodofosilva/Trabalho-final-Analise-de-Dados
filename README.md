cat > README.md << 'EOF'
# Análise Avançada de Dados — State of Data Brazil 2024

**Disciplina:** Análise Avançada de Dados
**Professora:** Ma. Heloisa Guimarães
**Instituição:** Centro Universitário Santo Agostinho — UNIFSA
**Autor:** Rodofo Dheymison e Carlos Arthur Moraes Gonçalves

## Pergunta Central

> Quais fatores mais influenciam o salário de um profissional de dados no Brasil em 2024?

## Resposta

Com base na análise do State of Data Brazil 2024–2025 (5.217 respondentes), os fatores que mais influenciam o salário são, em ordem de impacto: senioridade é o preditor mais forte, com correlação de Spearman significativa (p < 0,001) — a progressão de Júnior para Sênior representa a maior alavanca salarial. O tipo de cargo também pesa: ML/AI Engineers e Engenheiros de Dados têm medianas superiores às de Analistas de Dados e BI no mesmo nível. O tempo de experiência cresce progressivamente, com salto expressivo a partir de 5 anos. A região Sudeste concentra as maiores medianas. Por fim, a diferença salarial por gênero persiste mesmo controlada pela senioridade.

## Dashboard

Link: (adicionar link do Looker Studio)

## Estrutura do Repositório

- notebook/ — análise completa em Python
- relatorio/ — relatório narrativo em PDF
- dados/ — instruções para baixar o CSV

## Decisões de Limpeza

- Faixas salariais convertidas para ponto médio aritmético via regex
- 21 colunas renomeadas pelo dicionário oficial do Kaggle
- Missings em gênero e raça não foram imputados
- Registros sem cargo ou senioridade filtrados para análise salarial
- Títulos de cargo agrupados em categorias simplificadas

## Referências

- Base: https://www.kaggle.com/datasets/datahackers/state-of-data-brazil-20242025
- Link: https://datastudio.google.com/reporting/8f245e54-996d-4c7f-aa74-76290ac8cbe4
- Bibliotecas: pandas, numpy, matplotlib, seaborn, scipy
- Data Hackers / Bain & Company
EOF
