# Strapi App

A **Strapi-based CMS application** for managing content with a modular and scalable setup. This project is structured to support **custom content types**, **API testing**, and **frontend integration**. It is ideal for building content-driven applications such as websites, dashboards, and internal tools.

---

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Project Structure](#project-structure)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
- [Available Scripts](#available-scripts)
- [Docker Setup](#docker-setup)
- [Testing](#testing)
- [Contributing](#contributing)
- [License](#license)

---

## Project Overview

This project is a **Strapi application** initialized with sample content types and ready to be deployed. It allows developers to quickly set up a backend CMS with REST or GraphQL API endpoints.  

The project is structured with Nx workspace conventions and includes configurations for testing, deployment, and CI/CD integrations.

---

## Features

- Modular content management
- REST and GraphQL API endpoints
- Pre-configured Nx workspace
- Testing setup with Jest for unit and integration tests
- Docker configuration for development and testing
- GitHub-friendly project structure

---

## Project Structure
strapi-app/
├─ .nxignore # Files and directories ignored by Nx
├─ .prettierrc.js # Prettier configuration
├─ docker-compose.dev.yml # Docker setup for development
├─ docker-compose.test.yml # Docker setup for testing
├─ jest.config.js # Jest configuration
├─ package.json # Project dependencies and scripts
├─ strapi-app/ # Main Strapi application folder
├─ yarn.lock # Yarn dependency lock file
└─ README.md # Project documentation

### Notable Files:

- `.nxignore`: Ensures unnecessary files are excluded from Nx operations.
- `docker-compose.dev.yml`: Sets up Strapi with Docker for local development.
- `jest.config.*.js`: Configurations for unit and integration tests.
- `package.json`: Contains scripts for running, building, and testing the project.

---

## Technologies Used

- **Node.js** – JavaScript runtime
- **Strapi** – Headless CMS
- **Nx** – Monorepo management
- **Docker** – Containerization
- **Jest** – Testing framework
- **Yarn** – Package manager
- **Git** – Version control

---

## Getting Started

Follow these steps to run the project locally:

### 1. Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/strapi-task.git
cd strapi-app
yarn install
yarn develop

Here is a high-level view of the important files and folders:

<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/42d07ed6-a218-42fc-baa0-7f8ec0075ac8" />
<img width="1919" height="917" alt="image" src="https://github.com/user-attachments/assets/9ea1311c-4e5d-4d86-8068-bf577d9392e7" />
