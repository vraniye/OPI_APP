# FastAPI Microservices Project

## Overview
This project contains two microservices:
1. **TODO Service**: Manages a list of tasks with CRUD operations.
2. **Short URL Service**: Provides URL shortening and redirection functionality.

## Project Structure
- `todo_service/`: Code for the TODO service.
- `short_url_service/`: Code for the Short URL service.
- `README.md`: Project documentation.

## Getting Started
### Prerequisites
- Python 3.10
- Docker & Docker Compose

### Build and Run
1. Build Docker images:
   ```bash
   docker build -t todo_service ./todo_service
   docker build -t short_url_service ./short_url_service
