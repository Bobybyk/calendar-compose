# docker-compose-repo

## Description

Ce dépôt contient les configurations Docker Compose pour déployer une application Node.js et MongoDB.

## Structure

- `docker-compose.yml` : Configure les services MongoDB, l'application Node.js et les scripts de configuration de la base de données.
- `Dockerfile` : Décrit comment construire l'image Docker pour l'application Node.js.

## Utilisation

1. **Assure-toi que les autres dépôts sont clonés** 
- `calendar-backend` 
- `calendar-db`

2. **Construire les images Docker :**

```bash
docker-compose build
```