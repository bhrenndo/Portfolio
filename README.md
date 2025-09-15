🤖 Projeto: Assistente de Políticas Internas com IA

Este projeto demonstra a criação de um Service Desk inteligente usando LangChain, RAG (Retrieval-Augmented Generation) e LangGraph.
Dentre suas Funcionalidades principais estão: Triagem automática de solicitações: classifica entre AUTO_RESOLVER, PEDIR_INFO ou ABRIR_CHAMADO. Base de conhecimento com RAG: busca em políticas internas (PDFs) usando embeddings + FAISS.  Orquestração com LangGraph: fluxo de decisão estruturado com nós para triagem, resolução, solicitação de informação e abertura de chamados.
Explicabilidade: respostas citam documento, página e trecho relevante e Feedback inteligente: quando não encontra resposta → pede mais informações ao usuário.

- Tecnologias utilizadas: Python, LangChain (prompts, RAG, embeddings), Google Gemini API (LLM principal), FAISS (armazenamento vetorial), LangGraph (fluxo orquestrado), Streamlit + ngrok (execução e exposição do app).
