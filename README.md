 Chatbot citoyen malien

POC – Assistant conversationnel bilingue français–bambara**

 1. Présentation du projet

Le projet Chatbot citoyen malien vise à développer un assistant conversationnel intelligent permettant aux citoyens d'accéder plus facilement aux informations relatives aux démarches administratives au Mali.

Le système prend en charge les échanges en français et en bambara et s'appuie sur des technologies de traitement automatique du langage naturel et d'intelligence artificielle.

 2. Objectifs

- Faciliter l'accès aux informations administratives.
- Permettre aux citoyens de poser leurs questions en français ou en bambara.
- Fournir des réponses adaptées au contexte de la conversation.
- Centraliser les informations et les services administratifs.
- Préparer une architecture évolutive et modulaire.

 3. Architecture générale

Le projet est organisé autour de trois composantes principales :

 Front-end
Contient les interfaces destinées aux citoyens et aux administrateurs.

- `chatbot-ui/` : interface conversationnelle.
- `admin-ui/` : interface d'administration.

 Back-end
Gère les API, les services applicatifs, la sécurité et l'accès aux données.

### DSP (Data Science Platform)
Regroupe les composants d'intelligence artificielle :

- Traitement du langage naturel.
- Reconnaissance des intentions.
- Embeddings français et bambara.
- Rasa et modèles d'intelligence artificielle.
- Reconnaissance et synthèse vocales (ASR/TTS).

 4. Organisation du repository

chatbot-citoyen-malien/
├── frontend/
├── backend/
├── dsp/
├── contracts/
├── deploy/
├── scripts/
├── tests/
├── docs/
├── README.md
└── .gitignore

 5. Technologies

Les technologies seront précisées et documentées au fur et à mesure du développement.

- Python
- Rasa
- PostgreSQL
- API REST
- gRPC
- Traitement automatique du langage naturel
- Technologies Front-end à définir

 6. Équipe et collaboration

Le projet est développé en collaboration entre les membres de l'équipe, sous la supervision de l'encadreuse.

Les développements sont organisés à travers Git et GitHub, avec des branches dédiées et des Pull Requests.

 7. État du projet

**Phase actuelle :** Proof of Concept (POC) et structuration de l'architecture cible.

 8. Licence

Projet en cours de développement. Les conditions de distribution seront définies ultérieurement.
