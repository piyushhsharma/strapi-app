🚀 Strapi CMS Project

This repository contains a Strapi-powered content management system built with scalability and simplicity in mind.
It provides a solid backend foundation for handling content, APIs, and integrations with modern frontend applications.

This setup works well for:

Business and personal websites

Admin or management dashboards

Content-focused platforms

Internal or tooling applications

📚 Contents

Overview

Key Capabilities

Folder Structure

Tech Stack

Setup Guide

Useful Commands

Docker Usage

Testing

Contribution Guide

License

🧩 Overview

The project is a preconfigured Strapi application designed to help developers get started quickly.
It enables you to create and manage content through a web-based admin panel while exposing data through REST or GraphQL APIs.

Using an Nx workspace layout, the project stays organized and ready for growth, making it suitable for collaborative development and automated workflows.

⭐ Key Capabilities

Structured and customizable content management

API support using REST and GraphQL

Built-in admin interface for managing data and users

Workspace management with Nx

Test-ready setup using Jest

Docker-based environment for consistency

Clean and maintainable repository structure

📁 Folder Structure
strapi-app/
├─ .nxignore                 # Nx ignore rules
├─ .prettierrc.js            # Code formatting rules
├─ docker-compose.dev.yml    # Docker configuration for development
├─ docker-compose.test.yml   # Docker configuration for testing
├─ jest.config.js            # Test configuration
├─ package.json              # Scripts and dependencies
├─ strapi-app/               # Core Strapi project
├─ yarn.lock                 # Dependency lock file
└─ README.md                 # Documentation

Important Files

.nxignore – Prevents Nx from tracking unnecessary files

docker-compose.dev.yml – Spins up Strapi using Docker

jest.config.js – Handles test setup

package.json – Defines commands and dependencies

🧰 Tech Stack

Node.js – JavaScript execution environment

Strapi – Headless CMS platform

Nx – Workspace and monorepo tooling

Docker – Container-based setup

Jest – Testing framework

Yarn – Dependency management

Git – Source control

⚙️ Setup Guide

Follow these steps to run the application on your local machine.

Step 1: Clone the repository
git clone https://github.com/YOUR_USERNAME/strapi-task.git
cd strapi-app

Step 2: Install required packages
yarn install

Step 3: Launch the development server
yarn develop


Access the admin panel at:

http://localhost:1337/admin


Create an admin account and start working with content.

🧾 Useful Commands
Command	Purpose
yarn develop	Run Strapi locally in dev mode
yarn build	Compile the admin dashboard
yarn start	Start the app in production
yarn test	Execute test suites
🐋 Docker Usage

To start the project using Docker for development:

docker-compose -f docker-compose.dev.yml up


To run tests in Docker:

docker-compose -f docker-compose.test.yml up


This ensures the same environment across machines.

🧪 Testing

Testing is handled using Jest.

Run all tests with:

yarn test


You can expand the test coverage by adding your own unit or integration tests.

🤝 Contribution Guide

If you’d like to contribute:

Fork this repository

Create a feature branch

Implement your changes

Open a pull request

📄 License

This project is open for educational and development use.
You are free to adapt and extend it according to your needs.