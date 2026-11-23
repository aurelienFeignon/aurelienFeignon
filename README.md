🇬🇧 English · [🇫🇷 Français](./README.fr.md)

# Hi, I'm Aurélien Feignon

Full Stack Developer based in Tours, France. I build real-time, event-driven systems, from React
interfaces to distributed backends, ML pipelines and LLM agents.

## What I'm working on

**Augure** *(personal project since 2025, private repository)*: a real-time predictive platform.
TypeScript/Python monorepo, 48 containerized services and ~30 RabbitMQ workers, an ML pipeline
(TensorFlow/Keras, XGBoost, NVIDIA Triton inference) and an agentic AI assistant with 27 tools on a
multi-provider LLM layer (Anthropic, OpenAI, Ollama), traced with Arize Phoenix. Architecture
decisions are documented as RFCs and ADRs.

**Askor** *(since 2021)*: Full Stack Developer on a life-cycle assessment (LCA) and eco-design
software. React Flow and Zustand on the front end, a Symfony API Platform REST API, an asynchronous
calculation engine (Symfony Messenger + a Python microservice), real-time updates with Mercure and
Highcharts visualizations.

## Featured projects

- **[debian-host-audit](https://github.com/aurelienFeignon/debian-host-audit)**: read-only security
  audit of Debian 13 hosts in one container (Lynis, docker-bench-security, Trivy and custom checks),
  merged into one report built for humans and AI agents. Signed images with SBOM on GHCR.
  *Python · Docker · GitHub Actions*
- **[hephaistos3d](https://github.com/aurelienFeignon/hephaistos3d)**: self-hosted web app that turns
  a 2D image into a 3D object (Gaussian Splatting) on your own NVIDIA GPU, with a job queue and real
  progress tracking. *In development.* *Python · FastAPI · PyTorch · Next.js · Three.js · Docker*
- **[bonsai-server](https://github.com/aurelienFeignon/bonsai-server)**: configurable,
  OpenAI-compatible LLM server for NVIDIA GPUs, with verified, resumable model downloads.
  *llama.cpp · CUDA · Docker · Python*
- **[rpsls-websocket](https://github.com/aurelienFeignon/rpsls-websocket)**: real-time two-player
  Rock Paper Scissors Lizard Spock with private rooms; the server is the source of truth and the
  protocol is shared across the monorepo. *React · Zustand · Node.js · Socket.IO*
- **Dedale** *(private, early stage)*: patent exploration engine with multi-source ingestion, hybrid
  lexical + vector search and answers grounded in the corpus.
  *TypeScript · Python · PostgreSQL · RabbitMQ · BGE-M3 · Next.js*

## Tech stack

| | |
|---|---|
| **Languages** | TypeScript, JavaScript, Python, PHP, SQL, Bash |
| **Backend** | Node.js, Express, Symfony, API Platform, Symfony Messenger, FastAPI, Prisma, REST, Socket.IO, Mercure, RabbitMQ |
| **Data & ML** | PostgreSQL, TimescaleDB, Redis, TensorFlow/Keras, XGBoost, PyTorch, NVIDIA Triton |
| **AI & agents** | Tool-calling agents, Anthropic, OpenAI, Ollama, llama.cpp, Arize Phoenix, hybrid search |
| **Frontend** | React, Next.js, Zustand, React Flow, Highcharts, Three.js, Vite |
| **Infra** | Docker, Docker Compose, Traefik, GitHub Actions, Prometheus, Grafana |

## Contact

[LinkedIn](https://www.linkedin.com/in/aur%C3%A9lien-feignon-19a01820b/) ·
[aurelien.feignon@gmail.com](mailto:aurelien.feignon@gmail.com)
