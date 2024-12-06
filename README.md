# Chatbot---Assistant-Virtuel-pour-pr-senter-mon-CV
Chatbot - Assistant Virtuel pour présenter mon CV.

## Aperçu
Cette application Streamlit est un chatbot interactif conçu pour mettre en valeur mon parcours professionnel et mes qualifications. En s'appuyant sur des Large Language Models (LLM) et un cadre Retrieval Augmented Generation (RAG), elle fournit des réponses précises et contextuelles basées sur mon CV et d'autres données stockées dans un fichier CSV et un fichier pdf. Le chatbot utilise un FAISS vector store pour une récupération efficace des informations et le modèle OpenAI GPT-3.5-turbo pour générer des réponses. Streamlit offre une interface conviviale pour une interaction fluide.

## Fonctionnalités
- Basé sur le RAG : Utilise une approche de génération augmentée par récupération pour garantir des réponses pertinentes et fondées sur les informations fournies.
- Q&A interactif : Permet aux utilisateurs de poser des questions et de recevoir des réponses informatives directement issues des données CSV/PDF.
- Historique des conversations : Conserve les conversations dans MongoDB Atlas pour des analyses ultérieures et une meilleure expérience utilisateur.
- Connaissance des limites : Gère avec élégance les situations où le chatbot ne dispose pas des informations nécessaires pour répondre, garantissant une expérience fluide.
- Suggestions de questions : Propose des suggestions pour guider les utilisateurs et encourager une exploration approfondie de mes qualifications.

## Lien vers l'application Streamlit
Voici le lien de démonstration de mon assistant virtuel : <>.

## Prérequis
- Python 3.9 ou version ultérieure
- Clé API OpenAI
- Compte MongoDB Atlas
- Compte Streamlit pour héberger l'application
