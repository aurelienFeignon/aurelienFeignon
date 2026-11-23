[🇬🇧 English](./README.md) · 🇫🇷 Français

# Bonjour, moi c'est Aurélien Feignon

Développeur Full Stack basé à Tours. Je conçois des systèmes temps réel et event-driven, de
l'interface React jusqu'aux backends distribués, aux pipelines ML et aux agents LLM.

## En ce moment

**Augure** *(projet personnel depuis 2025, dépôt privé)* : une plateforme prédictive temps réel.
Un monorepo TypeScript/Python, 48 services conteneurisés et ~30 workers RabbitMQ, un pipeline ML
(TensorFlow/Keras, XGBoost, inférence NVIDIA Triton) et un assistant IA agentique doté de 27 outils,
sur une couche LLM multi-fournisseurs (Anthropic, OpenAI, Ollama) observée avec Arize Phoenix. Les
choix d'architecture sont consignés dans des RFC et des ADR.

**Askor** *(depuis 2021)* : développeur Full Stack sur un logiciel d'analyse de cycle de vie (ACV) et
d'éco-conception. React Flow et Zustand côté front, une API REST Symfony API Platform, un moteur de
calcul asynchrone (Symfony Messenger + un microservice Python), du temps réel avec Mercure et des
visualisations Highcharts.

## Projets à la une

- **[debian-host-audit](https://github.com/aurelienFeignon/debian-host-audit)** : audit de sécurité
  en lecture seule des hôtes Debian 13, dans un seul conteneur (Lynis, docker-bench-security, Trivy et
  des contrôles maison), réunis dans un rapport unique lisible par un humain comme par un agent IA.
  Images signées, avec SBOM, publiées sur GHCR. *Python · Docker · GitHub Actions*
- **[hephaistos3d](https://github.com/aurelienFeignon/hephaistos3d)** : application web auto-hébergée
  qui transforme une image 2D en objet 3D (Gaussian Splatting) sur votre propre GPU NVIDIA, avec file
  de jobs et suivi réel de la progression. *En développement.*
  *Python · FastAPI · PyTorch · Next.js · Three.js · Docker*
- **[bonsai-server](https://github.com/aurelienFeignon/bonsai-server)** : serveur LLM paramétrable,
  compatible OpenAI, pour GPU NVIDIA, avec téléchargement des modèles vérifié et reprenable.
  *llama.cpp · CUDA · Docker · Python*
- **[rpsls-websocket](https://github.com/aurelienFeignon/rpsls-websocket)** : Pierre-Feuille-Ciseaux-
  Lézard-Spock à deux joueurs en temps réel, avec salons privés ; le serveur fait foi et le protocole
  est partagé dans le monorepo. *React · Zustand · Node.js · Socket.IO*
- **Dedale** *(privé, premiers stades)* : moteur d'exploration de brevets, avec ingestion
  multi-sources, recherche hybride lexicale + vectorielle et réponses ancrées dans le corpus.
  *TypeScript · Python · PostgreSQL · RabbitMQ · BGE-M3 · Next.js*

## Stack technique

| | |
|---|---|
| **Langages** | TypeScript, JavaScript, Python, PHP, SQL, Bash |
| **Backend** | Node.js, Express, Symfony, API Platform, Symfony Messenger, FastAPI, Prisma, REST, Socket.IO, Mercure, RabbitMQ |
| **Data & ML** | PostgreSQL, TimescaleDB, Redis, TensorFlow/Keras, XGBoost, PyTorch, NVIDIA Triton |
| **IA & agents** | Agents à tool-calling, Anthropic, OpenAI, Ollama, llama.cpp, Arize Phoenix, recherche hybride |
| **Frontend** | React, Next.js, Zustand, React Flow, Highcharts, Three.js, Vite |
| **Infra** | Docker, Docker Compose, Traefik, GitHub Actions, Prometheus, Grafana |

## Contact

[LinkedIn](https://www.linkedin.com/in/aur%C3%A9lien-feignon-19a01820b/) ·
[aurelien.feignon@gmail.com](mailto:aurelien.feignon@gmail.com)
