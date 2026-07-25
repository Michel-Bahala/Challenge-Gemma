# Challenge-Gemma
PESA DISPO est une plateforme intelligente d'octroi de crédit multi-secteur propulsée par l'IA (LightGBM & Gemma) et Gradio. Elle automatise et sécurise l'analyse des dossiers pour particuliers, entreprises et jeunes entrepreneurs en moins de 5 secondes.

🌟 Fonctionnalités Principales
Gestion Multi-Secteur : Traitement segmenté et structuré pour les Prêts Particuliers, Prêts Entreprises et Prêts Jeunes Entrepreneurs via des tables SQLite dédiées.

IA Hybride & Scoring Avancé : Combine LightGBM pour l'évaluation quantitative des risques et un grand modèle de langage (google/gemma-4-E2B-it) pour générer des rapports décisionnels argumentés et en texte brut.

Import de Fichiers : Possibilité d'insérer des fichiers justificatifs au format .csv pour injecter des données contextuelles directement dans l'analyse.

Assistants Conversationnels : Un chatbot contextuel intégré dans chaque onglet pour interroger l'IA sur les motifs précis d'acceptation ou de refus des dossiers.

Synthèse Vocale (Option Speak) : Restitution audio des rapports et décisions grâce à la technologie gTTS.

Interface sur-mesure : Design Fintech moderne avec un thème sombre épuré, des blocs de lecture optimisés et des boutons d'action en vert émeraude.

🛠️ Stack Technique
Langage : Python

Interface Graphique : Gradio

Machine Learning & IA : LightGBM, Hugging Face Transformers, BitsAndBytes (quantification 4-bit)

Base de Données : SQLite (synchronisée avec Google Drive)

Manipulation de Données : Pandas, NumPy

Audio : gTTS (Google Text-to-Speech)

📦 Installation et Lancement
Clonez le dépôt :

Bash
https://github.com/Michel-Bahala/Challenge-Gemma
cd pesa-dispo
Installez les dépendances :
Utilisez le fichier requirements.txt fourni :

Bash
pip install -r requirements.txt
