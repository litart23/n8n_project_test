# n8n starter kit

**n8n starter Kit** is an open-source Docker Compose template designed to swiftly initialize a comprehensive local AI and low-code development environment.

Curated by <https://github.com/n8n-io>, it combines the self-hosted n8n platform with a curated list of compatible AI products and components to
quickly get started with building self-hosted AI workflows.

### What’s included

✅ [**Self-hosted n8n**](https://n8n.io/) - Low-code platform with over 400
integrations and advanced AI components

✅ [**Ollama**](https://ollama.com/) - Cross-platform LLM platform to install
and run the latest local LLMs

✅ [**Qdrant**](https://qdrant.tech/) - Open-source, high performance vector
store with an comprehensive API

✅ [**PostgreSQL**](https://www.postgresql.org/) -  Workhorse of the Data
Engineering world, handles large amounts of data safely.

## Installation

### Cloning the Repository

```bash
git clone https://github.com/n8n-io/self-hosted-ai-starter-kit.git
cd self-hosted-ai-starter-kit
```

### Running n8n using Docker Compose

If you want to download ollama as a part of a docker container:

```
docker compose --profile cpu up
```

If you want to use your local ollama, that already running on your machine:
```
docker compose up
```

## ⚡️ Quick start and usage

To open n8n at any time, visit <http://localhost:5678/> in your browser.

Create your account.

On the first page <http://localhost:5678/home/workflows> click "Demo workflow"

On the Editor page click "Open chat" button in the bottom of the screen

In opened text field write your message -- you will see an answer in the chat


