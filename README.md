# Symfony 6.3 Docker Starter

This is an empty Symfony setup with Docker for anyone wanting to develop a Symfony 6.3 application from scratch.

## Getting Started

These instructions will help you set up a local development environment for your Symfony application.

### Prerequisites

- Docker
- Docker Compose
- Git

### Usage

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/sorbaugh/symfony63-docker-starter.git
   cd symfony63-docker-starter
   ```
2. Build and start the Docker containers:
   ```bash
   docker-compose up -d
   ```
3. Install Symfony dependencies:
   ```bash
   docker-compose exec php_symfony63_app composer install
   ```
4. Access your Symfony application in a web browser:
   - Symfony: http://localhost:9000
   - phpMyAdmin: http://localhost:8080

### Contributing
Feel free to contribute to this starter template. If you have improvements or suggestions, please create a pull request.