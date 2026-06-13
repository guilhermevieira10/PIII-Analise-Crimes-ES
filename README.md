# PIII - Observatorio Criminal ES

Projeto Integrador III - Ciencia da Computacao | FAESA

Este projeto consiste em uma solucao de Ciencia de Dados aplicada a Seguranca Publica do Espirito Santo. A proposta evoluiu de uma analise estatistica inicial para um MVP web interativo, com paineis, indicadores, mapas, rankings, heatmaps e insights voltados ao apoio a tomada de decisao.

O foco principal e a analise de crimes no Espirito Santo, especialmente crimes contra o patrimonio, crimes contra a vida, mobilidade urbana, crimes informaticos e apreensao de armas de fogo.

## Objetivo

Desenvolver um painel web capaz de transformar bases publicas de criminalidade em informacoes visuais e estrategicas, facilitando a identificacao de padroes por municipio, bairro, horario, tipo de ocorrencia e local do fato.

## Sociedade Impactada

A solucao impacta:

- populacao do Espirito Santo;
- gestores publicos;
- orgaos de seguranca;
- pesquisadores;
- estudantes;
- imprensa local.

O painel busca tornar dados publicos mais acessiveis, compreensiveis e uteis para analise social e planejamento de acoes preventivas.

## MVP Final

O MVP final e um sistema web com:

- dashboard em tema escuro;
- filtros por municipio e periodo;
- KPIs de roubos, furtos, transporte coletivo e crimes informaticos;
- mapa do Espirito Santo com pontos de risco;
- rankings por municipio, bairro e tipo de local;
- mapas de calor por dia da semana e horario;
- analise de crimes contra o patrimonio;
- analise de crimes contra a vida;
- analise de mobilidade urbana e transporte coletivo;
- analise de crimes informaticos;
- analise de armas de fogo apreendidas;
- insights para tomada de decisao.

## Video de Apresentacao

Entrega 2 - Prototipo:

https://www.youtube.com/watch?v=xXmOBZiaBz4

Entrega 3 - MVP Final:

https://youtu.be/FFGJsSLa8hQ

## Tecnologias Utilizadas

- Python
- Pandas
- Jupyter Notebook / Google Colab
- HTML5
- CSS3
- JavaScript
- GitHub
- Bases publicas em CSV, XLSX e PDF

## Metodologia de Ciencia de Dados

O projeto seguiu as seguintes etapas:

1. Coleta de bases publicas de seguranca.
2. Tratamento e padronizacao dos dados.
3. Correcao de encoding, datas, horarios e municipios.
4. Remocao de registros inconsistentes.
5. Agrupamento por municipio, bairro, local, tipo de crime e horario.
6. Criacao de KPIs e indicadores.
7. Construcao de rankings e series temporais.
8. Aplicacao de analise estatistica, incluindo Teste T.
9. Geracao de mapas de calor.
10. Desenvolvimento do painel web interativo.

## Bases de Dados Utilizadas

Foram utilizadas bases publicas relacionadas a seguranca publica no Espirito Santo, incluindo:

- roubos 2024 e 2025;
- furtos 2024 e 2025;
- crimes informaticos 2023 e 2024;
- historico de homicidios dolosos por municipio;
- homicidios, latrocinios e lesoes corporais;
- furto e roubo de celulares;
- furto e roubo de veiculos;
- furto e roubo a residencias;
- roubo e furto a comercio;
- roubo em via publica;
- bicicleta, celular e veiculo em 2025;
- armas de fogo apreendidas entre 2020 e 2024;
- Anuario Estadual de Seguranca Publica 2025;
- Mapa da Seguranca Publica 2025.

## Resultados e Insights

Alguns insights extraidos:

- Serra aparece com destaque em roubos, celulares, veiculos e apreensao de armas.
- Vitoria concentra alto volume de crimes informaticos e ocorrencias ligadas ao transporte coletivo.
- Campo Grande, Centro e Carapina aparecem como bairros relevantes no recorte de transporte coletivo.
- Via publica concentra grande parte dos registros de roubo.
- A analise por horario permite identificar janelas criticas para patrulhamento.
- O historico de homicidios mostra reducao estadual recente entre 2020 e 2024.
- Revolveres e pistolas sao os tipos mais comuns entre as armas apreendidas.
- O Teste T confirmou diferenca estatisticamente significativa entre Serra e Vila Velha nos roubos analisados.

## Como Executar o Projeto

Para abrir o painel localmente, acesse a pasta do projeto e execute:

```bash
python -m http.server 4173
```

Depois abra no navegador:

```text
http://127.0.0.1:4173
```

Tambem e possivel abrir diretamente o arquivo:

```text
index.html
```

## Estrutura do Projeto

```text
PIII-Analise-Crimes-ES/
├── index.html
├── dashboard-data.js
├── espirito-santo-mapa.svg
├── wagner.webp
├── notebooks/
│   ├── PIII.ipynb
│   ├── PI3_Anuarios_Visao_Geral.ipynb
│   ├── PI3_Crimes_Contra_Vida.ipynb
│   ├── PI3_Crimes_Patrimonio.ipynb
│   ├── PI3_Microdados_Patrimonio.ipynb
│   └── PI3_Mobilidade_Transporte.ipynb
├── dados/
└── README.md
```

## Grupo

- Guilherme Santos Vieira
- Davi Portugal Soares do Carmo
- Gabriel Schwan Vallentim
- Nicolas Andrade

## Status

MVP final desenvolvido para a Entrega 3 do Projeto Integrador III, contendo aplicacao web, analise de dados, indicadores, visualizacoes e documentacao tecnica.

