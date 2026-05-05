# Inteligência Artificial: RAG e Bancos de Dados Vetoriais

![GitHub Repo Size](https://img.shields.io/github/repo-size/seu-usuario/seu-repositorio?style=for-the-badge)
![AI Knowledge](https://img.shields.io/badge/Area-Artificial_Intelligence-blue?style=for-the-badge&logo=openai)
![Status](https://img.shields.io/badge/Status-Concluído-brightgreen?style=for-the-badge)
![Institution](https://img.shields.io/badge/Instituição-FATESG%20/%20SENAI-red?style=for-the-badge)

Este repositório contém o material das pesquisas acadêmicas desenvolvidas para a disciplina de Inteligência Artificial, focadas em técnicas de recuperação de informação e armazenamento semântico.

---

## 🎯 Objetivos Acadêmicos
O objetivo central deste trabalho é explorar as tecnologias que solucionam os problemas de "alucinação" e a falta de atualização em tempo real dos Grandes Modelos de Linguagem (LLMs).
* Compreender o funcionamento da arquitetura **RAG (Retrieval-Augmented Generation)**.
* Analisar o papel fundamental dos **Bancos de Dados Vetoriais** na infraestrutura de IA.
* Diferenciar buscas exatas (tradicionais) de buscas por similaridade semântica (vetoriais).

---

## 🔍 Resumo das Pesquisas

### 1. RAG - Retrieval-Augmented Generation
A pesquisa detalha a técnica de **Geração Aumentada por Recuperação**, que atua como uma ponte entre modelos de linguagem e fontes de dados externas.

* **Problema Resolvido:** Redução de alucinações e atualização constante do conhecimento sem necessidade de retreinar o modelo.
* **O Fluxo RAG:**
    1.  **Query:** A pergunta inicial do usuário.
    2.  **Embedding Model:** Conversão do texto em "vetores" (idioma matemático).
    3.  **VectorDB:** Busca por contextos relevantes no banco de dados.
    4.  **LLM:** Processamento do contexto recuperado para gerar uma resposta precisa.
* **Variações:** Naive RAG, Advanced RAG, Modular RAG, Graph RAG, RAG Híbrido e Self-RAG.

### 2. Bancos de Dados Vetoriais
Foca na infraestrutura que permite a busca por significado (semântica) em vez de apenas palavras-chave.

* **Conceito de Vetor:** Representação numérica do significado de dados (textos, imagens ou áudios).
* **Busca por Similaridade:** Utilização de métricas como Similaridade de Cosseno, Distância Euclidiana e Produto Interno para encontrar dados "próximos".
* **Ferramentas Analisadas:**
    * **Qdrant:** Alta performance e segurança de memória (desenvolvido em Rust).
    * **Pinecone:** Escalabilidade em nuvem.
    * **Weaviate & Milvus:** Foco em grandes escalas e busca híbrida.
    * **Chroma & pgvector:** Simplicidade e integração com sistemas existentes.

---

## 🛠️ Metodologia e Tecnologias
A pesquisa foi realizada através de análise técnica de arquiteturas de sistemas e ferramentas de mercado.

| Tecnologia | Função no Ecossistema |
| :--- | :--- |
| **LLMs** | Geração de respostas inteligentes (ChatGPT, Gemini, Claude). |
| **Embeddings** | Tradução de conceitos humanos para o idioma computacional. |
| **Busca Semântica** | Recuperação de informação baseada no sentido, não na letra. |
| **Qdrant / Rust** | Armazenamento e indexação de alta velocidade. |

---

## 📈 Vantagens e Características
* **Atualização em tempo real:** Novos dados podem ser adicionados ao banco sem custos de treinamento.
* **Rastreabilidade:** É possível identificar a fonte exata que embasou a resposta da IA.
* **Custo-benefício:** Técnica eficaz para tornar IAs especialistas em negócios específicos de forma econômica.

---
> "O RAG é uma ponte inteligente entre a criatividade dos modelos de linguagem e a precisão das bases de dados."
---

## 🎓 Autor
- **Felipe Mendonça Branquinho**
- **Instituição:** Faculdade FATESG / SENAI
