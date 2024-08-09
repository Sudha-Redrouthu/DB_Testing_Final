# Online Bookstore API

## Description
This is an API for an Online Bookstore. It allows for CRUD operations on authors, books, customers, genres, publishers, and reviews. The project utilizes TypeScript with Node.js and Express, and connects to a PostgreSQL database using TypeORM. Docker is used for containerization.

## Project Structure
- **src/**
  - **controllers/**: Contains the controller files for managing API routes.
  - **entities/**: Defines the TypeORM entities for the database tables.
  - **routes/**: Contains the route definitions for the API endpoints.
  - **services/**: Contains the service files for handling business logic.
  - **data-source.ts**: Configures the TypeORM data source.
  - **index.ts**: Main entry point for the application.
- **Dockerfile**: Docker configuration for building the project container.
- **docker-compose.yml**: Docker Compose configuration for managing containers.
- **README.md**: This file.

## Setup

### Prerequisites
- Node.js and npm
- PostgreSQL
- Docker

### Installation

1. **Clone the repository:**
   ```bash
   git clone <repository-url>
   cd <repository-directory>
