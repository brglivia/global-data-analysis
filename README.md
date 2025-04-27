# 🌎 Análise de Dados Globais: População, Renda e Pesquisas Estatísticas por País

## 🎯 Objetivo

Este projeto tem como objetivo analisar dados estatísticos fornecidos pelo Banco Mundial. Exploramos informações de 247 países e territórios relacionadas a censos populacionais, grupos de renda, registros vitais e dados agrícolas, industriais e comerciais.

---

## 📊 Dados

Os dados analisados foram extraídos de um arquivo .CSV disponibilizado pelo Banco Mundial e contêm informações sobre:

**Censos Populacionais** (Última coleta de dados populacionais) 

**Pesquisas de Domicílios** (Última pesquisa realizada sobre condições de vida) 

**Registro Civil Completo** (Completude dos registros vitais) 

**Dados Agrícolas** (Última coleta de dados sobre agricultura) 

**Dados Industriais** (Última coleta de dados sobre a indústria) 

**Dados Comerciais e de Comércio** (Últimos dados sobre comércio) 

**Dados sobre Retirada de Água** (Últimos dados sobre consumo de água) 

---

## 🛠️ Tecnologias

Python (Bibliotecas: pandas, matplotlib, seaborn)
Jupyter Notebook

---

## 📥 Como Rodar

**1. Requisitos**
Certifique-se de ter o Python instalado em seu ambiente local, assim como as bibliotecas necessárias. Você pode instalar as dependências com o seguinte comando:
bash
Copiar
Editar
pip install pandas matplotlib seaborn

**2. Obtenha os Dados**
Baixe o arquivo Country.csv fornecido pelo Banco Mundial. Coloque o arquivo na mesma pasta do notebook ou ajuste o caminho do arquivo no código.

**3. Rodando o Notebook**
Abra o notebook Análise_de_Dados_Globais.ipynb em seu ambiente Jupyter e execute as células. O código irá carregar os dados e gerar as visualizações de distribuição de renda, censos populacionais e registros civis.

---

## 📈 Análise

**1. Distribuição dos Países por Grupo de Renda**
Este gráfico mostra a quantidade de países distribuídos entre os diferentes grupos de renda (Baixo, Médio, Alto), com base nas informações do Banco Mundial.

**2. Ano do Último Censo Populacional**
A distribuição dos anos dos censos populacionais revela uma concentração maior de censos realizados nas últimas duas décadas, refletindo a crescente ênfase na coleta de dados populacionais.

**3. Registro Civil Completo por Grupo de Renda**
Analisando a completude dos registros vitais, observamos que países de baixa renda têm mais dificuldades em manter registros civis completos, indicando uma relação entre o nível de renda e a qualidade dos registros vitais.

---

## ✅ Conclusões

**Registro civil completo por grupo de renda:** A análise mostrou que países de baixa renda tendem a ter um maior número de países sem registros civis completos, o que pode indicar uma relação entre o nível econômico e a qualidade dos registros vitais.

**Distribuição do ano do último censo:** Observou-se uma maior concentração de censos populacionais realizados nas últimas duas décadas, refletindo uma crescente ênfase na coleta de dados populacionais.

**Visão global dos dados do Banco Mundial:** Os dados fornecidos pelo Banco Mundial oferecem uma visão ampla sobre o estágio de desenvolvimento estatístico entre os países. Este projeto analisou informações sobre censos populacionais, grupos de renda, registros vitais e outros dados socioeconômicos, mas há muitas outras áreas a explorar.

---

## 📌 Melhorias Futuras

**Análise Regional:** Investigar possíveis padrões regionais e comparar diferentes continentes.

**Relação entre Renda e Dados Socioeconômicos:** Correlacionar dados como registros vitais, censos e outros aspectos com a renda dos países.

**Análise Temporal:** Analisar as mudanças ao longo do tempo em cada um desses fatores.
