# Agentic RAG with LangGraph

Ce projet implémente un agent IA capable d'effectuer du **RAG (Retrieval-Augmented Generation)** et d'exécuter des outils personnalisés pour répondre à des requêtes complexes. Il est basé sur l'écosystème **LangChain** et orchestré par **LangGraph**.

## 🚀 Fonctionnalités

- **RAG Personnel** : Utilisation de `ChromaDB` et `OpenAIEmbeddings` pour indexer et interroger des informations sur le profil de l'utilisateur (parcours, projets comme ShowBay et SMA44).
- **Multi-Tooling** : L'agent a accès à plusieurs outils :
  - Recherche documentaire (CV).
  - Consultation d'informations employés (Simulation).
  - Envoi d'e-mails (Simulation).
- **Modèle de pointe** : Propulsé par `GPT-4o` pour un raisonnement logique et une sélection précise des outils.

## 🛠️ Stack Technique

- **Framework** : [LangChain](https://python.langchain.com/) / [LangGraph](https://langchain-ai.github.io/langgraph/)
- **LLM** : OpenAI GPT-4o
- **Base de données vectorielle** : ChromaDB
- **Environnement** : Python 3.13+ (géré via `pyproject.toml`)

## 📋 Prérequis

- Un compte OpenAI (pour la clé API).
- Python 3.13 installé.

## ⚙️ Installation

1. Clonez le dépôt :
```bash
git clone <url-du-repo>
cd agentic_ai_with_langchain
