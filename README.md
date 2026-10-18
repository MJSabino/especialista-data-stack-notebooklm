# 🚀 Especialista em Data Stack: Da Coleta ao Business Intelligence com Gemini Notebook

Projeto prático de estudo onde construí uma **base de conhecimento interativa sobre Modern Data Stack (MDS)** utilizando o Gemini Notebook (NotebookLM). O objetivo foi criar um assistente especialista para me ajudar a navegar, estruturar e entender conceitos essenciais da engenharia de dados, utilizando exclusivamente fontes de alta qualidade selecionadas e validadas.

---

## 🎯 Por Que Este Estudo?

- **Tema:** Modern Data Stack (MDS) — Da Coleta ao BI.
- **Objetivo:** *Organizar uma base confiável de conhecimento para entender na prática como funcionam as arquiteturas modernas de dados, desde a ingestão (ELT), armazenamento colunar até a transformação analítica.*

---

## 📚 Fontes Que Selecionei e Confio

Para garantir respostas precisas e sem "alucinações", selecionei a dedo artigos técnicos, documentações e vídeos explicativos. Dividi todas as 13 fontes em três categorias principais:

1. **🌐 Artigos e Documentações Web:**
   - [Arquitetura Medalhão - O Guia Definitivo Para Organizar o Data Lakehouse](https://blog.dsacademy.com.br/arquitetura-medalhao-o-guia-definitivo-para-organizar-o-data-lakehouse-fundamentos/) (Data Science Academy)
   - [dbt (Data Build Tool) em Projetos de Engenharia Analítica](https://blog.dsacademy.com.br/dbt-data-build-tool-em-projetos-de-engenharia-analitica/) (Data Science Academy)
   - [Glossário de terminologia técnica da Databricks](https://docs.databricks.com/gcp/pt/resources/glossary) (Databricks on Google Cloud)
   - [Mapa de Carreiras na Área de Dados na Era da IA](https://blog.dsacademy.com.br/mapa-de-carreiras-na-area-de-dados-na-era-da-ia/) (Data Science Academy)
   - [Python and REST APIs: Interacting With Web Services](https://realpython.com) (Real Python)
   - [What is RAG (Retrieval Augmented Generation)?](https://ibm.com) (IBM)

2. **📺 Vídeos no YouTube:**
   - Curso Completo de Power BI | Aula 17 - Storytelling com Dados na Prática
   - Estudo de Caso 1 - Batch, Streaming ou Ambos?
   - ETL vs ELT — A Diferença Que Aparece em Quase Toda Entrevista de Engenharia de Dados
   - Formato Parquet
   - O Que é Big Data: Como Ele Está Transformando a Tomada de Decisões
   - O que é BANCO DE DADOS e porque INTERESSA APRENDER isso?

3. **📄 Documentos e Arquivos:**
   - `SQL.pdf` (Apostila e guia teórico/prático sobre SQL e SGBDs)

---

## 🤖 Como Treinei o Notebook (Instrução de Comportamento)

Para evitar respostas genéricas e manter o foco técnico, defini a seguinte diretriz de comportamento para o assistente:

> *"Comporte-se como um Engenheiro e Arquiteto de Dados especialista em Modern Data Stack. Responda às dúvidas de forma clara, didática e estritamente embasada nas fontes fornecidas, destacando as diferenças entre ETL e ELT, a arquitetura de Data Lakehouse e os formatos de armazenamento de dados."*

---

## 💬 Testando o Notebook: Perguntas e Achados

Aqui estão quatro perguntas fundamentais que fiz ao notebook para validar se ele estava de fato extraindo o conhecimento correto das fontes selecionadas:

### 1. Entendendo o Conceito Geral
> **Pergunta:** *O que é Data Stack? E como isso pode auxiliar no desenvolvimento?*
- **O que aprendi com a resposta:** O notebook sintetizou que uma Data Stack é a combinação de ferramentas para todo o ciclo de vida dos dados. Ele destacou 5 camadas essenciais (da coleta com Fivetran/Airbyte à transformação com dbt) e explicou como isso acelera o desenvolvimento de soluções analíticas.
- **Fontes usadas na resposta:** Fontes `1`, `2`, `3` e `7`.
- **Evidência do Chat:**

![O que é Data Stack](assets/print-1-data-stack.jpeg)

---

### 2. Arquitetura de Armazenamento
> **Pergunta:** *Quais são as camadas do Data Lakehouse?*
- **O que aprendi com a resposta:** Ele explicou a famosa Arquitetura Medalhão (popularizada pela Databricks), mostrando o papel da camada **Bronze** (dados brutos mantidos de forma imutável com *Schema-on-Read*), da camada **Prata** (limpeza e validação) e da camada **Ouro** (pronta para os dashboards).
- **Fontes usadas na resposta:** Fontes `1`, `2` e `3`.
- **Evidência do Chat:**

![Camadas do Data Lakehouse](assets/print-2-data-lakehouse.jpeg)

---

### 3. Formato e Performance
> **Pergunta:** *Como funciona o formato Parquet?*
- **O que aprendi com a resposta:** A resposta trouxe detalhes técnicos valiosos sobre como o Parquet usa orientação a colunas, metadados embutidos e leitura seletiva para economizar processamento em grandes volumes de dados.
- **Fontes usadas na resposta:** Fontes `1`, `4` e `5`.
- **Evidência do Chat:**

![Formato Parquet](assets/print-3-parquet.jpeg)

---

### 4. Mudança de Paradigma
> **Pergunta:** *Quais são as principais diferenças entre as arquiteturas ETL e ELT?*
- **O que aprendi com a resposta:** A principal virada de chave foi entender que, no ELT moderno, primeiro carregamos os dados brutos no Data Warehouse para depois transformá-los lá dentro, aproveitando o poder computacional da nuvem (ao contrário do ETL tradicional, que exigia servidores intermediários pesados).
- **Fontes usadas na resposta:** Fontes `1`, `2`, `4`, `5` e `7`.
- **Evidência do Chat:**

![ETL vs ELT](assets/print-4-etl-vs-elt.jpeg)

---

## 🎨 Materiais de Estudo Gerados no Estúdio

A partir da consolidação do conhecimento das fontes no Gemini Notebook, gerei o mapa mental visual para sintetizar os conceitos e pilares da área:

- 🧠 **Mapa Mental Completo:**

![Mapa Mental Data Stack](assets/NotebookLM-Mind-Map.jpg)

- 📖 **Guia de Estudos / Documentos:**
  - [Acessar Guia em PDF](materiais/guia-de-estudos-data-stack.pdf) *(opcional se tiver subido o PDF)*

---

## 🔗 Acesse o Meu Notebook

Fique à vontade para explorar o caderno e navegar pelas fontes e citações:

- 🚀 [Abrir o Gemini Notebook — Data Stack: Da Coleta ao BI](https://notebook.google.com/notebook/e37d5494-5655-4664-8390-78631c950252?authuser=3)

> *Nota: O notebook está configurado como público/compartilhado e não contém dados pessoais.*
