🚀 Strapi App

A Strapi-based CMS application designed for managing content with a modular, scalable, and developer-friendly setup.
This project supports custom content types, API development, testing, and easy frontend integration.

It’s suitable for building:

Websites

Admin dashboards

Content-driven applications

Internal tools

📑 Table of Contents

Project Overview

Features

Project Structure

Technologies Used

Getting Started

Available Scripts

Docker Setup

Testing

Contributing

License

📌 Project Overview

This is a Strapi CMS application initialized with a clean structure and sample configurations.
It allows developers to quickly spin up a backend with REST or GraphQL APIs, manage content via an admin panel, and connect it seamlessly with any frontend framework.

The project follows Nx workspace conventions, making it suitable for scalable development, testing, and CI/CD workflows.

✨ Features

Modular content management using Strapi

REST & GraphQL API support

Admin dashboard for content and user management

Nx-based workspace configuration

Jest setup for unit & integration testing

Docker support for development and testing

Clean, GitHub-friendly project structure

📂 Project Structure
strapi-app/
├─ .nxignore                 # Files and directories ignored by Nx
├─ .prettierrc.js            # Prettier configuration
├─ docker-compose.dev.yml    # Docker setup for development
├─ docker-compose.test.yml   # Docker setup for testing
├─ jest.config.js            # Jest configuration
├─ package.json              # Project dependencies and scripts
├─ strapi-app/               # Main Strapi application
├─ yarn.lock                 # Yarn dependency lock file
└─ README.md                 # Project documentation

Notable Files

.nxignore – Excludes unnecessary files from Nx operations

docker-compose.dev.yml – Runs Strapi locally using Docker

jest.config.js – Configuration for testing

package.json – Scripts for running, building, and testing

🛠️ Technologies Used

Node.js – JavaScript runtime

Strapi – Headless CMS

Nx – Monorepo & workspace management

Docker – Containerization

Jest – Testing framework

Yarn – Package manager

Git – Version control

🚀 Getting Started

Follow these steps to run the project locally.

1️⃣ Clone the Repository
git clone https://github.com/YOUR_USERNAME/strapi-task.git
cd strapi-app

2️⃣ Install Dependencies
yarn install

3️⃣ Start Development Server
yarn develop


Once running, open the admin panel:

http://localhost:1337/admin


Create your admin account and start managing content.

📜 Available Scripts
Command	Description
yarn develop	Start Strapi in development mode
yarn build	Build the admin panel
yarn start	Start Strapi in production mode
yarn test	Run tests using Jest
🐳 Docker Setup

To run the application using Docker:

docker-compose -f docker-compose.dev.yml up


For testing:

docker-compose -f docker-compose.test.yml up


This setup helps maintain consistent environments across development and testing.

🧪 Testing

The project uses Jest for testing.

To run tests:

yarn test


Both unit and integration tests can be added under the configured test folders.

🤝 Contributing

Contributions are welcome!

Fork the repository

Create a new branch

Make your changes

Submit a pull request

📄 License

This project is open-source and available for learning and development purposes.
You are free to use and modify it as needed.