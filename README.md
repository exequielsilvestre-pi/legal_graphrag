# 🧠⚖️ Legal GraphRAG (Prueba)

Este proyecto es una **prueba de viabilidad** de un sistema **GraphRAG legal** utilizando:

- [LangChain](https://www.langchain.com/)
- [Neo4j](https://neo4j.com/)
- [Azure OpenAI](https://azure.microsoft.com/en-us/products/cognitive-services/openai-service)
- [Docker](https://www.docker.com/)

El objetivo fue testear el funcionamiento de un **RAG (Retrieval-Augmented Generation)** apoyado en una base de conocimiento en forma de grafo con **Neo4j** y embebidos usando **Azure OpenAI**.

---

## 🛠️ Tecnologías

- `LangChain`: para el pipeline de RAG y conectividad con embeddings.
- `Neo4j`: grafo de conocimiento que almacena los documentos y sus embeddings.
- `Azure OpenAI`: para generar embeddings y eventualmente generar respuestas.
- `Docker Compose`: para levantar Neo4j con los volúmenes y configuraciones necesarias.

---

## 🚀 Cómo correrlo

1. Cloná el repositorio:

```bash
git clone https://github.com/tu_usuario/tu_repo.git
cd tu_repo
```

### 2. Creá el archivo .env y configurá tus variables

### 3. Levantá Neo4j con Docker
```bash
docker-compose up -d
```
