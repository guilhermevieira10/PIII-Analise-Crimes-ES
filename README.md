# 📊 PIII - Análise de Dados de Segurança Pública (ES)
**Projeto Integrador III - Ciência da Computação | FAESA**

Este projeto consiste em um pipeline de Ciência de Dados para análise e extração de insights sobre a criminalidade no estado do Espírito Santo, com foco em crimes contra o patrimônio (roubos). O objetivo é fornecer suporte estatístico e visual para a tomada de decisões táticas em segurança pública.

## 🎥 Apresentação do Protótipo (Entrega 2)
Assista ao vídeo demonstrativo onde apresento o código funcionando, a interpretação do Teste T e os insights gerados pelo dashboard:
👉 **[Link do Vídeo no YouTube](https://www.youtube.com/watch?v=xXmOBZiaBz4)**

## 🛠️ Tecnologias e Metodologia
O projeto foi desenvolvido em **Python** utilizando o ambiente **Google Colab**. As principais etapas incluíram:

- **ETL (Extração e Limpeza):** Tratamento de bases de dados abertos e anuários de segurança, padronização de datas e limpeza de valores nulos.
- **Estatística Inferencial (Teste T):** Aplicação do Teste t de Student para validar se a diferença nas médias de roubos entre os municípios de Serra e Vila Velha é estatisticamente significativa (p < 0,05).
- **Análise Visual (Data Viz):**
    - **Boxplot:** Análise de dispersão e identificação de *outliers* diários.
    - **Heatmap:** Mapa de calor cruzando dias da semana e horários de pico.
    - **Séries Temporais:** Aplicação de Média Móvel de 7 dias para identificação de tendências de longo prazo.

## 📈 Resultados e Insights
- **Validação Matemática:** O Teste T confirmou que a Serra possui uma média de roubos significativamente superior a Vila Velha, rejeitando a hipótese nula.
- **Inteligência Tática:** O Mapa de Calor identificou janelas críticas de criminalidade (ex: segundas-feiras às 19h), permitindo o direcionamento otimizado de patrulhamento.
- **Localização:** Mapeamento dos 5 bairros com maior incidência para suporte a cercos táticos.

## 🧑‍💻 Autor
- **Guilherme Santos Vieira**
- Estudante de Ciência da Computação - FAESA (5º Período)

---
*Este repositório faz parte das atividades acadêmicas do Projeto Integrador III.*
