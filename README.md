# rag-container

This repository contains code to containerize the [RAG stack](https://github.com/psychic-api/rag-stack) using Docker Compose.

## Contents

- `docker-compose.yml` - Defines the RAG stack services
- `backend/` - Backend API code and Dockerfile 
- `frontend/` - Frontend React app code and Dockerfile
- `scripts/` - Helper scripts

## Services

The docker-compose file defines the following services:

- `backend` - RAG backend API 
- `frontend` - React frontend
- `qdrant` - Vector database
