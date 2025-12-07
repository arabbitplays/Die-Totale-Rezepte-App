# Die-Total-Rezepte-App

A fully Dockerized recipe and shopping-list application built with Angular, Spring Boot, and MongoDB.
The app lets you create recipes with ingredients and cooking steps, classify ingredients as fresh or non-fresh, and add all fresh ingredients from any recipe to your shopping list with a single click.

## Features

Create, update, and manage recipes.
Mark ingredients as fresh or non-fresh.
Auto-generate a shopping list from all fresh ingredients in selected recipes.

## Building 

- Prerequisites
    - Docker & Docker Compose
    - Node.js + Angular CLI (if developing the frontend)
    - Java 17+ (if developing the backend)

```
# Run container with
docker compose up --build
```

Access the frontend under [http://localhost:4200]

## Environment Configuration

The application requires a `.env` file in the project root.
These variables configure MongoDB initialization and the application user.
See `.env.example` for more.

