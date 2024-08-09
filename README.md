# Online Bookstore API

## Description
This is an API for an Online Bookstore. It allows for CRUD operations on authors, books, customers, genres, publishers, and reviews. The project utilizes TypeScript with Node.js and Express, and connects to a PostgreSQL database using TypeORM. Docker is used for containerization.

# Group 11
## Sudha Karthikeyan Mohan
 
## Responsibilities
 
## sudha
 
- Database Setup
- Implementing CRUD functionalties
- Data migration
 
## Karthik
 
- Integration testing
- Entity relationship diagram
 
## Mohan
 
- Readme.md file
- Unit testing

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
  

### Prerequisites
- Node.js and npm
- PostgreSQL
- Docker
### Install Dependencies
- npm install
### Configure environment variables
- DB_HOST=localhost
- DB_PORT=5432
- DB_USERNAME=postgres
- DB_PASSWORD=newpassword
- DB_DATABASE=onlinebookstore
### Run the application
- npm start
### Running with Docker
## Build the Docker image
- docker build -t onlinebookstore-api .
## Run Docker Compose
- docker-compose up
### Project Structure
- src/: Contains the source code for the project.

  - controllers/: Contains controller files for handling requests and responses.
    - entities/: Contains TypeORM entity definitions for the database tables.
    - routes/: Contains route definitions for the API endpoints.
    - services/: Contains business logic and service layer files.
    - data-source.ts: Configures the TypeORM data source.
    - index.ts: Entry point for the application.

- docker-compose.yml: Docker Compose configuration file.

- Dockerfile: Dockerfile for building the application image.

- .env: Environment configuration file.

- README.md: This file.
### Testing
- npm test
### Contributing
- Fork the repository and create a new branch for your changes.
- Make your changes and ensure that all tests pass.
- Submit a pull request with a detailed description of your changes.



