# llm-playground

inspired by: <https://www.youtube.com/watch?v=DYhC7nFRL5I>

## Components used

- [Docker](https://www.docker.com/)
- [Open-Webui](https://docs.openwebui.com/)
- [ollama](https://ollama.com/)

## Getting started

The web application [Open-Webui](https://docs.openwebui.com/), as used in the docker compose already contains the [ollama](https://ollama.com/) service.

Start the app with `docker compose up -d` and head to `http://localhost:3000` when the container has spun up.

There will not be a model pre-installed but you can easily add a model as shown [here](https://docs.openwebui.com/getting-started/quick-start/starting-with-ollama#a-quick-and-efficient-way-to-download-models).

For a first try, I'd go with something small like `llama3.2:1b`. So you would just enter that into the field, press pull and wait for it to download.

Done.

## Configure container to use NVIDIA GPU

Install the Nvidia Container Toolkit

see: <https://hub.docker.com/r/ollama/ollama>
