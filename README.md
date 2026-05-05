# Inteligência Artificial: RAG e Bancos de Dados Vetoriais

![GitHub Repo Size](https://img.shields.io/github/repo-size/seu-usuario/seu-repositorio?style=for-the-badge)
![AI Knowledge](https://img.shields.io/badge/Area-Artificial_Intelligence-blue?style=for-the-badge&logo=openai)
![Status](https://img.shields.io/badge/Status-Concluído-brightgreen?style=for-the-badge)
![Institution](https://img.shields.io/badge/Instituição-FATESG%20/%20SENAI-red?style=for-the-badge)

Este repositório contém uma série de pesquisas acadêmicas desenvolvidas para a disciplina de Inteligência Artificial, focadas em técnicas modernas de recuperação de informação e armazenamento semântico.

---

## 🎯 Objetivos Acadêmicos
O objetivo principal destas pesquisas é explorar as tecnologias que resolvem os problemas de "alucinação" e falta de atualização em tempo real dos Grandes Modelos de Linguagem (LLMs).
* Compreender o funcionamento da arquitetura **RAG (Retrieval-Augmented Generation)**.
* Analisar o papel crítico dos **Bancos de Dados Vetoriais** na IA moderna.
* Diferenciar buscas exatas (SQL) de buscas por similaridade semântica.

---

## 🔍 Resumo das Pesquisas

### 1. RAG - Retrieval-Augmented Generation
[cite_start]A pesquisa aborda a técnica de **Geração Aumentada por Recuperação**, que conecta modelos de linguagem a fontes de dados externas e confiáveis[cite: 12, 16].

* [cite_start]**Problema Resolvido:** Mitigação de alucinações e atualização de conhecimento sem necessidade de retreinamento[cite: 15, 73].
* **Componentes do Fluxo:**
    1.  [cite_start]**Query:** A pergunta do usuário[cite: 19].
    2.  [cite_start]**Embedding Model:** Transformação de texto em vetores matemáticos[cite: 22, 23].
    3.  [cite_start]**VectorDB:** Onde os textos convertidos são armazenados e buscados[cite: 26, 27].
    4.  [cite_start]**LLM:** O "cérebro" que formula a resposta final baseada no contexto recuperado[cite: 33, 34].
* [cite_start]**Tipos de RAG Pesquisados:** Naive RAG, Advanced RAG, Modular RAG, Graph RAG, RAG Híbrido e Self-RAG[cite: 54, 57, 60, 63, 66, 69].

### 2. Bancos de Dados Vetoriais
[cite_start]Foca na infraestrutura que permite a busca por significado em vez de apenas palavras-chave exatas[cite: 94, 95].

* [cite_start]**Funcionamento:** Utiliza vetores (listas de números) para representar o sentido de textos, imagens ou áudios[cite: 95, 96].
* [cite_start]**Métricas de Similaridade:** Similaridade de Cosseno, Distância Euclidiana e Produto Interno[cite: 106, 107, 109, 110].
* **Principais Ferramentas:**
    * [cite_start]**Qdrant:** Alta performance em Rust (Destaque da pesquisa)[cite: 118, 137].
    * [cite_start]**Pinecone:** Serviço gerenciado em nuvem[cite: 121, 122].
    * [cite_start]**Chroma:** Ideal para protótipos locais[cite: 126, 127].
    * [cite_start]**pgvector:** Extensão vetorial para PostgreSQL[cite: 131, 132].

---

## 🛠️ Metodologia e Tecnologias
A pesquisa foi estruturada através de análise bibliográfica de documentações técnicas e frameworks de IA.

| Tecnologia | Função |
| :--- | :--- |
| **LLMs** | [cite_start]Geração de respostas baseadas em contexto (GPT, Gemini, Claude)[cite: 35]. |
| **Embeddings** | [cite_start]Tradução de linguagem humana para vetores matemáticos[cite: 25, 101]. |
| **Busca Semântica** | [cite_start]Recuperação de informação por similaridade (ANN)[cite: 105, 113]. |
| **Rust / Python** | [cite_start]Linguagens base para as ferramentas de alta performance citadas[cite: 137]. |

---

## 📈 Características Principais das Tecnologias
* [cite_start]**Rastreabilidade:** Possibilidade de saber a fonte exata da resposta da IA[cite: 75].
* [cite_start]**Custo-benefício:** Mais barato que treinar modelos do zero[cite: 77].
* [cite_start]**Alta Dimensionalidade:** Capacidade de lidar com vetores de milhares de dimensões[cite: 112].
* [cite_start]**Escalabilidade:** Suporte a bilhões de vetores com buscas em milissegundos[cite: 114].

---
> [cite_start]"O RAG é uma ponte inteligente entre a criatividade dos modelos de linguagem e a precisão das bases de dados." [cite: 79]
---

## 🎓 Autor
- **Felipe Mendonça Branquinho**
- **Instituição:** Faculdade FATESG / SENAI
