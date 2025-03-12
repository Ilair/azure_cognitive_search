# Lab Project 04 - Azure Cognitive Search: Indexação e Consulta de Dados com AI Search  

![Status](https://img.shields.io/badge/Status_Projeto:-Concluído_(27/Mar/2024)-green)  

![Inteligência Artificial](https://img.shields.io/badge/Inteligência_Artificial_(IA)-blue)  
![Document Intelligence](https://img.shields.io/badge/Document_Intelligence-blue)  
![Indexação](https://img.shields.io/badge/Indexing-blue)  
![Microsoft Azure](https://img.shields.io/badge/Microsoft_Azure-blue)  
![Azure Cognitive Search](https://img.shields.io/badge/Azure_Cognitive_Search-blue)  
![Azure AI Search Index](https://img.shields.io/badge/Azure_AI_Search_Index-blue)  

---

## Introdução  

Este laboratório tem como objetivo explorar ferramentas de **indexação, pesquisa e inteligência documental** por meio do **Azure AI Search**. O experimento faz parte do **Bootcamp Microsoft Azure AI Fundamentals, da DIO**.  

A **Inteligência Documental (Document Intelligence)** é uma das áreas onde a **Inteligência Artificial** se mostra extremamente eficaz. Essa abordagem permite extrair informações relevantes de documentos de maneira automática, proporcionando mais eficiência no processamento de dados.  

Dentre as aplicações dessa tecnologia, podemos destacar:  

- **Reconhecimento óptico de caracteres (OCR)** para extrair texto de imagens e documentos digitalizados.  
- **Indexação automática** de conteúdos, facilitando a busca em grandes volumes de dados.  
- **Extração de palavras-chave e insights** a partir de textos.  
- **Análise de sentimentos**, permitindo classificar avaliações de clientes.  

Neste laboratório, utilizamos **técnicas de mineração de conhecimento (Knowledge Mining)** para obter insights sobre avaliações de consumidores de uma loja de café fictícia, criando um **Azure AI Search Index** a partir dessas avaliações.  

📌 **Mais detalhes podem ser encontrados no guia oficial da Microsoft:**  
[Explore an Azure AI Search Index (UI)](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/11-ai-search.html).  

---

## Procedimento  

Para a implementação do **Document Intelligence**, foram utilizados três recursos no **Azure**:  

1. **Azure AI Search** – responsável pela indexação e busca nos documentos.  
2. **Azure AI Services** – fornece ferramentas de IA para enriquecimento dos dados.  
3. **Storage Account** – armazenamento dos documentos em **Blob Containers**.  

![Arquitetura do Processo](https://source.unsplash.com/800x400/?cloud,data)  

---

## Upload de Dados e Criação do Index  

As avaliações utilizadas neste experimento podem ser acessadas por meio do link:  
🔗 [Coffee Reviews Dataset](https://aka.ms/mslearn-coffee-reviews).  

Após criar o **Blob Storage**, os arquivos foram carregados no repositório.  

![Upload de Arquivos](https://source.unsplash.com/800x400/?data,upload)  

Com os documentos armazenados, foi possível utilizar o **Azure AI Search** para criar um **índice** e extrair **insights** automaticamente. Essa configuração foi realizada por meio do assistente do portal **Azure**, permitindo a importação e indexação dos dados.  

![Configuração do Index](https://source.unsplash.com/800x400/?technology,search)  

Durante essa etapa, foram selecionadas as **habilidades (skills)** mais adequadas ao contexto dos documentos para aprimorar a análise e extração de informações.  

---

## Consulta de Dados no Index  

O **Azure AI Search** permite realizar consultas estruturadas no índice criado. Os resultados das buscas são retornados no formato **JSON**.  

Na imagem abaixo, vemos uma consulta filtrando as avaliações de clientes da cidade de **Chicago**.  

![Consulta por Localização](https://source.unsplash.com/800x400/?city,map)  

Também é possível refinar a pesquisa para identificar avaliações com **sentimento negativo**, utilizando técnicas de **análise de sentimentos**.  

![Análise de Sentimentos](https://source.unsplash.com/800x400/?ai,analytics)  

Além disso, foram extraídas **palavras-chave (keyphrases)** das avaliações, permitindo identificar rapidamente os principais tópicos mencionados pelos clientes. Esse processo facilita a compreensão geral do conteúdo analisado.  

---

## Conclusão e Insights  

Na era da informação, armazenar grandes volumes de dados não é suficiente – é essencial **analisar e extrair conhecimento útil** a partir dessas informações.  

Ferramentas de **Inteligência Documental** possibilitam a automação desse processo, tornando viável a análise de grandes quantidades de dados que, manualmente, seriam impossíveis de processar. Empresas que aplicam essas técnicas obtêm **insights estratégicos valiosos**, aprimorando suas tomadas de decisão e otimizando suas operações.  

📌 **Principais benefícios do uso do Azure AI Search:**  
✅ Indexação eficiente de documentos.  
✅ Busca rápida e estruturada em grandes bases de dados.  
✅ Extração de insights com análise de sentimentos e palavras-chave.  
✅ Automação do processamento de informações textuais.  

![Data Analytics](https://source.unsplash.com/800x400/?data,insights)  

---  

### 🔗 **Links úteis**  

- [Explore AI Search no Azure](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/11-ai-search.html)  
- [Document Intelligence no Azure](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/10-document-intelligence.html)  
- [Introdução ao Azure Cognitive Services](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/09-cognitive-services.html)  
