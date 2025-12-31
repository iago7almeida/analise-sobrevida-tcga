# Impacto de Mutações Genéticas na Sobrevida de Pacientes (TCGA)

## 📌 Visão Geral
Este projeto investiga a relação entre mutações genéticas somáticas e a sobrevida global de pacientes diagnosticados com carcinoma invasivo de mama. Utilizando dados do **The Cancer Genome Atlas (TCGA) – PanCancer Atlas**, o objetivo é identificar se mutações em genes *driver* específicos impactam estatisticamente o prognóstico dos pacientes.

## 🎯 Objetivos
- Analisar dados clínicos e genômicos do TCGA.
- Aplicar técnicas de Análise de Sobrevida (Kaplan-Meier, Cox Proportional Hazards).
- Avaliar a significância estatística da presença de mutações na sobrevida global.

## 🛠️ Tecnologias Utilizadas
- **Python 3**
- **Pandas & NumPy:** Manipulação e limpeza de dados.
- **Lifelines:** Biblioteca especializada em análise de sobrevida.
- **Matplotlib & Seaborn:** Visualização de dados.

## 📊 Metodologia
1. **Coleta de Dados:** Extração de dados clínicos e de mutações do TCGA.
2. **Pré-processamento:** Tratamento de valores nulos, censura de dados e categorização de variáveis.
3. **Análise Exploratória (EDA):** Distribuição demográfica e frequência de mutações.
4. **Modelagem de Sobrevida:**
   - Curvas de Kaplan-Meier para comparar grupos (Mutado vs. Selvagem).
   - Teste Log-Rank para validação estatística.

## 📈 Resultados Chaves
*(Aqui você deve inserir uma imagem de um gráfico importante do seu notebook e uma breve conclusão)*
> Exemplo: A análise indicou que mutações no gene TP53 apresentam uma correlação significativa com a redução da sobrevida em pacientes acima de 50 anos.

## 🚀 Como Executar
1. Clone este repositório:
   ```bash
   git clone (https://github.com/iago7almeida/analise-sobrevida-tcga)
