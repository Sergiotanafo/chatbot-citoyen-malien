# Chatbot citoyen malien — POC

## Présentation

Ce dépôt est consacré au **Proof of Concept (POC)** du projet Chatbot citoyen malien.

Il constitue la première version expérimentale du projet. Son objectif est de démontrer la faisabilité technique d'un chatbot capable d'interagir avec les citoyens en français et en bambara.

## Objectifs du POC

- Démontrer la faisabilité d'un chatbot citoyen bilingue français–bambara.
- Expérimenter le traitement automatique du langage naturel avec Rasa.
- Évaluer l'utilisation des embeddings pour améliorer la compréhension des requêtes.
- Tester les mécanismes de recherche et de génération de réponses.
- Évaluer les premières fonctionnalités de traitement vocal (ASR et TTS), selon leur niveau d'intégration.

## Périmètre du dépôt

Ce dépôt accueille exclusivement les travaux relatifs au POC :

- Conservation du prototype existant.
- Corrections et améliorations expérimentales.
- Tests et évaluations techniques.
- Documentation de l'état du prototype.
- Sécurisation du code et des données du POC.

**Important :** ce dépôt n'est pas destiné au développement de la version industrialisée.

## Organisation des branches

| Branche | Utilisation |
|---|---|
| `main` | Version stable et de référence du POC |
| `develop` | Intégration des évolutions du POC |
| `feature/*` | Développement de fonctionnalités spécifiques |

## Organisation du projet

L'architecture présente dans ce dépôt constitue une structure de travail initiale. Elle pourra évoluer en fonction de l'état réel du prototype.

## Sécurité et bonnes pratiques

- Ne jamais publier de mots de passe, clés API ou secrets.
- Ne pas versionner de données personnelles ou confidentielles.
- Documenter les modifications importantes.
- Tester les changements avant leur intégration dans `main`.

## Dépôts associés : industrialisation

La version industrialisée du projet est développée séparément dans trois dépôts :

- **Frontend** : https://github.com/Sergiotanafo/chatbot-citoyen-frontend
- **Backend** : https://github.com/Sergiotanafo/chatbot-citoyen-backend
- **DSP** : https://github.com/Sergiotanafo/chatbot-citoyen-dsp

## Statut du projet

POC — Phase de sécurisation et de documentation.

La version industrialisée fera l'objet d'un développement distinct.
