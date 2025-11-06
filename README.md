# 🧠 Introduction à l’IA générative et au RAG

Ce projet est une introduction à l’intelligence artificielle générative.  
L’objectif est de comprendre les bases des **grands modèles de langage (LLM)** et du **RAG (Retrieval-Augmented Generation)** à travers des exercices pratiques.

---

## 🎯 Objectifs pédagogiques

- Découvrir la génération de texte avec `transformers` et un modèle open-source.
- Comprendre le rôle des **embeddings** dans la recherche sémantique.
- Manipuler un index **FAISS** pour retrouver des passages similaires.
- (Optionnel) Créer un mini pipeline **RAG** combinant recherche + génération.

---

## 🧩 Contenu du notebook

1. **Génération de texte**  
   Utilisation du pipeline `text-generation` de Hugging Face avec le modèle `GPT-2`.

2. **Embeddings et FAISS**  
   Génération de vecteurs à l’aide de `sentence-transformers` et indexation avec `faiss-cpu`.

3. **Recherche de passages similaires**  
   Utilisation de la similarité cosinus (ou L2) pour retrouver les phrases les plus proches d’une requête donnée.

4. **Mini RAG (optionnel)**  
   Combinaison de la recherche et de la génération pour produire des réponses contextuelles.

---

## ⚙️ Installation

Installation des dépendances nécessaires :

```bash
pip install -r requirements.txt
